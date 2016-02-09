#### Test 5841644866d9c0e_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  950): acquireWL(354e8327): PARTIAL_WAKE_LOCK  *alarm* 0x1 950 1000 WorkSource{10072}
V/AlarmManager(  950): sending alarm PendingIntent{358de9d4: PendingIntentRecord{38a3577d com.android.vending startService}}, i=null, t=0, cnt=1, w=1455019809595, Int=0
V/AlarmManager(  950): sending alarm PendingIntent{9e28672: PendingIntentRecord{28962ac3 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455019812738, Int=536832000
V/AlarmManager(  950): sending alarm PendingIntent{db53846: PendingIntentRecord{19727a07 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455019804756, Int=20000
,--------- beginning of main
V/CheckinService( 4230): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
D/PMS     (  950): acquireWL(1ec9cf40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4230 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  950): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  950): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  950):     Client/Owner: Client
D/WifiDisplayAdapter(  950):     GroupId: 
D/WifiDisplayAdapter(  950):     Passphrase: 
D/WifiDisplayAdapter(  950):     SessionId: 0
D/WifiDisplayAdapter(  950):     IP Address: }
E/WifiStateMachine(  950): handleMessage: E msg.what=131143
D/PMS     (  950): releaseWL(354e8327): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:67 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=7.0 list=2412 [on:0 tx:0 rx:0 period:708] from screen [on:0 period:-974100573]
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:67 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=7.0 list=2412 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-974100573]
E/WifiStateMachine(  950): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.21 rxSuccessRate=6.99 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-63
E/WifiStateMachine(  950): WifiStateMachine CMD_START_SCAN with age=59626 interval=60000 maxinterval=300000
E/WifiStateMachine(  950): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  950): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  950): has c0:ff:d4:d3:aa:48 freq=2412 age=714 ?=true
E/WifiStateMachine(  950): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
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
D/wpa_supplicant( 1324): wlan0: Add radio work 'scan'@0x556c538860
D/wpa_supplicant( 1324): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1324): wlan0: Starting radio work 'scan'@0x556c538860 after 0.000038 second wait
D/wpa_supplicant( 1324): wlan0: nl80211: scan request
D/wpa_supplicant( 1324): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1324): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1324): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1324): wlan0: Own scan request started a scan in 0.000096 seconds
I/wpa_supplicant( 1324): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  950): [1,455,019,812,774 ms] noteScanstart no scan source
E/WifiStateMachine(  950): handleMessage: X
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  950): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  950): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  950): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/PMS     (  950): acquireWL(1ce97be): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4230 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  950): releaseWL(1ec9cf40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4230): Checking schedule, now: 1455019812795 next: 1455019812738
I/CheckinService( 4230): active receiver: enabled
I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4230, uid=10024, userID:0
I/CheckinService( 4230): Preparing to send checkin request
I/EventLogService( 4230): Accumulating logs since 1455019778458
D/wpa_supplicant( 1324): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1324): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1324): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1324): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1324): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1324): wlan0: Scan completed in 0.048158 seconds
D/wpa_supplicant( 1324): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1324): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1324): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1324): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1324): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1324): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1324): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
D/wpa_supplicant( 1324): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1324): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1324): wlan0: Scan-only results received
D/wpa_supplicant( 1324): wlan0: Radio work 'scan'@0x556c538860 done in 0.049112 seconds
E/WifiMonitor(  950): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  950): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  950): handleMessage: E msg.what=147461
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  950): processMsg: ConnectModeState
E/WifiStateMachine(  950):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  950): processMsg: DriverStartedState
E/WifiStateMachine(  950):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  950): processMsg: SupplicantStartedState
E/WifiStateMachine(  950):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  950): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1324): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  950): [1,455,019,812,828 ms] noteScanEnd no scan source
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  950): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@ec5d9f9 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  950): NG7005g c0:ff:d4:d3:aa:4a rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  950): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  950): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  950): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  950):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-63 freq=2412
E/WifiAutoJoinController (  950): Gonzos 38:f8:89:11:e9:11 rssi=-79 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  950): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  950): ageScanResultsOut delay 40000 size 4 now 1455019812832
E/WifiAutoJoinController (  950): newSupplicantResults size=4 known=1 true
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1324): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  950): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  950): ssid=NG700
E/WifiAutoJoinController (  950): id=0
E/WifiAutoJoinController (  950): mode=station
E/WifiAutoJoinController (  950): pairwise_cipher=CCMP
E/WifiAutoJoinController (  950): group_cipher=CCMP
E/WifiAutoJoinController (  950): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  950): wpa_state=COMPLETED
E/WifiAutoJoinController (  950): ip_address=192.168.1.130
E/WifiAutoJoinController (  950): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  950): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  950): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  950): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  950): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController (  950): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  950): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-63 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  950): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  950): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  950): Done attemptAutoJoin status=0
E/WifiConfigStore(  950):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  950): handleMessage: X
I/CheckinRequestBuilder( 4230): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  950): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4230): Failed to find provider info for com.google.android.wearable.settings
I/art     (  950): Explicit concurrent mark sweep GC freed 38987(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/25MB, paused 1.813ms total 156.957ms
E/cutils-trace( 6321): Error opening trace file: Permission denied (13)
D/Finsky  ( 5982): [597] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5982): [1] 5.onFinished: Installation state replication succeeded.
I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/CheckinRequestBuilder( 4230): awaiting user notification for token
D/CustomizationManager( 6321): ====startRecUseTime====
D/htc.customization.log.level( 6321):  is 
W/CustomizationLogLevel( 6321): Level value is invalid, use default level 2
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1220): reapply : com.google.android.gms 2 40
I/ActivityManager(  950): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6337 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 6337): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6337): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/CustomizationManager( 6321):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 6321): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6321): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6321): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6321): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6321): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6321): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6321): Parsing tag item name = HTC__031
I/MultiDex( 6337): VM with version 2.1.0 has multidex support
I/MultiDex( 6337): install
I/MultiDex( 6337): VM has multidex support, MultiDex support library is disabled.
V/CustomizationCIDLoader( 6321): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6321): Parsing tag category name = system
I/CustomizationCIDLoader( 6321): Parsing tag category name = application
I/CustomizationCIDLoader( 6321): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6321): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6321): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6321): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6321): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6321): add string-array item, value = 42507
I/CustomizationCIDLoader( 6321): add string-array item, value = 21902
I/CustomizationCIDLoader( 6321): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6321): add string-array item, value = 23420
I/CustomizationCIDLoader( 6321): add string-array item, value = 22299
I/CustomizationCIDLoader( 6321): add string-array item, value = 24002
I/CustomizationCIDLoader( 6321): add string-array item, value = 23210
I/CustomizationCIDLoader( 6321): add string-array item, value = 23205
I/CustomizationCIDLoader( 6321): add string-array item, value = 23806
I/CustomizationCIDLoader( 6321): add string-array item, value = 23430
I/CustomizationCIDLoader( 6321): add string-array item, value = 23408
I/CustomizationCIDLoader( 6321): add string-array item, value = 27205
I/CustomizationCIDLoader( 6321): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6321): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6321):  Read CID file spent 0.112 (s)
D/CustomizationManager( 6321):  All configurations done spent 0.112 (s)
V/JNIHelp ( 6337): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  950): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6321 on display 0
D/PMS     (  950): acquireHCC(7ae6c6e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 950 1000 null
D/PMS     (  950): acquireHCC(3561df0f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 950 1000 null
W/ActivityThread( 6337): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6337): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@232852c9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6337): Installed default security provider GmsCore_OpenSSL
W/asset   (  950): Copying FileAsset 0x559f9d96b0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  950): acquireWL(2f58e17a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 950 1000 null
I/AnimationUtil(  950): isHTCRecent(ThaliTest/Recent screens.)/5
D/GCM     ( 1921): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/FeedHostManager( 1505): [onPause]
I/FeedProviderManager( 1505): onPause
D/AuthorizationBluetoothService( 1921): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4230): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/FeedHostManager( 1505): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@16ef5fcb
I/SocialFeedProvider( 1505): +onPause
I/SocialFeedProvider( 1505): -onPause
W/HtcSystemUPManager(  950): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  950): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6363 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  950):  packet count Tx=152 Rx=296
E/WifiTrafficPoller(  950): notifying of data activity 1
I/art     (  412): Explicit concurrent mark sweep GC freed 8682(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 755us total 29.422ms
D/WIFI_ICON( 1220): WifiActivity: 1
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/art     (  412): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 246us total 15.881ms
D/WearableService( 5694): callingUid 10024, callindPid: 5694
E/MDM     ( 1825): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/art     (  412): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 364us total 16.186ms
D/StatusBarManagerService(  950): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  950): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  950): hiding MENU key
I/TrimMemoryManager( 1505): [trimMemory] 20
W/asset   ( 6363): Copying FileAsset 0xac404f08 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4230, uid=10024, userID:0
I/WVCdm   (  405): CdmEngine::OpenSession
I/WVCdm   (  405): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  405): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/LocationInitializer( 4230): Restart initialization of location
D/DrmWidevineDash(  405): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  405): Service_Initialize: starts!
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
E/QSEECOMAPI: (  405): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  405): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
D/QSEECOMAPI: (  405): Loaded image: APP id = 8
D/DrmWidevineDash(  405): Service_Initialize: ends! returns 0
D/QSAPPSVER(  405): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  405): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf47d2000
E/DrmWidevineDash(  405): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf47d2000
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  536): got the req here! ret=0
D/DrmLibTime(  536): command id, time_cmd_id = 770
D/DrmLibTime(  536): time_getutcsec starts!
D/DrmLibTime(  536): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  536): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  536): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  536): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  536): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  536): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  536): QSEE Time Listener: Retrieved Android system time: 1455019813
D/DrmLibTime(  536): time_getutcsec returns 0, sec = 1455019813; nsec = 0
D/DrmLibTime(  536): time_getutcsec finished! 
D/DrmLibTime(  536): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  536): before calling ioctl to read the next time_cmd
E/QC-time-services(  469): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/WebViewFactory( 6363): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  405): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: starts! SID=0xf4282928
D/DrmWidevineDash(  405): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: starts! randomData=0xab55a3e0, dataLength=8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab56da88, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  405): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  405): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  405): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  405): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: starts! deviceID=0xab6505b0, idLength=0xf48fc6f8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: starts!, current = 0xf48fc70e, maximum = 0xf48fc70f
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf48fc77c
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  405): PrepareKeyRequest: nonce=1274853504
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab55cab0
D/DrmWidevineDash(  405): message_length=1611, signature=0xab55a578, signature_length=0xf48fc6dc
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/LibraryLoader( 6363): Time to load native libraries: 10 ms (timestamps 8491-8501)
I/LibraryLoader( 6363): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6363): Binding Chromium to main looper Looper (main, tid 1) {3c395b7d}
I/LibraryLoader( 6363): Expected native library version number "",actual native library version number ""
I/chromium( 6363): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6363): Initializing chromium process, singleProcess=true
W/art     ( 6363): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6363): ApplicationContext is null in ApplicationStatus
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  405): CdmEngine::CloseSession
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  405): L3 Terminate.
D/DrmWidevineDash(  405): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): Service_Uninitialize: starts!
D/QSEECOMAPI: (  405): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  405): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  405): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  405): OEMCrypto_Terminate: ends! returns 0
W/chromium( 6363): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6363): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6363): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/WVCdm   (  405): CdmEngine::OpenSession
I/WVCdm   (  405): Level3 Library Sep 25 2014 17:10:03
I/Adreno-EGL( 6363): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6363): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6363): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6363): Local Branch: 
I/Adreno-EGL( 6363): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6363): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6363):                  d74aa161a12b9c6fc6332151
W/WVCdm   (  405): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  405): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  405): Service_Initialize: starts!
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
E/QSEECOMAPI: (  405): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  405): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
D/QSEECOMAPI: (  405): Loaded image: APP id = 9
D/DrmWidevineDash(  405): Service_Initialize: ends! returns 0
D/QSAPPSVER(  405): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  405): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf47d2000
E/DrmWidevineDash(  405): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf47d2000
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  536): got the req here! ret=0
D/DrmLibTime(  536): command id, time_cmd_id = 770
D/DrmLibTime(  536): time_getutcsec starts!
D/DrmLibTime(  536): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  536): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  536): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  536): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  536): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  536): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  536): QSEE Time Listener: Retrieved Android system time: 1455019813
D/DrmLibTime(  536): time_getutcsec returns 0, sec = 1455019813; nsec = 0
D/DrmLibTime(  536): time_getutcsec finished! 
D/DrmLibTime(  536): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  536): before calling ioctl to read the next time_cmd
E/QC-time-services(  469): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  405): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: starts! SID=0xf4282928
D/DrmWidevineDash(  405): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: starts! randomData=0xab55a5d0, dataLength=8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab56da88, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/System.err(  950): java.lang.Throwable: stack dump
W/System.err(  950): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  950): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  950): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  950): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  950): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  950): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1147fed0:true
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  405): CdmEngine::QueryKeyControlInfo
D/BluetoothAdapter( 6363): 629486201: getState(). Returning 12
W/WVCdm   (  405): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  405): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  405): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: starts! deviceID=0xab6505d0, idLength=0xf49fc6f8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: starts!, current = 0xf49fc70e, maximum = 0xf49fc70f
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf49fc77c
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  405): PrepareKeyRequest: nonce=861708986
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab5551f0
D/DrmWidevineDash(  405): message_length=1646, signature=0xab5225d8, signature_length=0xf49fc6dc
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/art     ( 6363): Attempt to remove local handle scope entry from IRT, ignoring
W/ContextImpl(  950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
W/AwContents( 6363): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6363): CordovaWebView is running on device made by: HTC
W/art     ( 6363): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6363): Attempt to remove local handle scope entry from IRT, ignoring
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  405): CdmEngine::CloseSession
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  405): L3 Terminate.
D/DrmWidevineDash(  405): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): Service_Uninitialize: starts!
D/QSEECOMAPI: (  405): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  405): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  405): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  405): OEMCrypto_Terminate: ends! returns 0
W/chromium( 6363): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
E/cutils-trace( 6418): Error opening trace file: Permission denied (13)
I/dex2oat ( 6418): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6418): dex2oat: override thread count:4
I/dex2oat ( 6418): dex2oat took 32.074ms (threads: 4)
D/FindExtension( 6363): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/Adreno-EGL( 6337): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6337): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6337): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6337): Local Branch: 
I/Adreno-EGL( 6337): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6337): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6337):                  d74aa161a12b9c6fc6332151
I/InputMethodManager( 6363): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@22291da5, mServedView=org.apache.cordova.engine.SystemWebView{2528157a VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1ef8812b
I/InputMethodManagerService(  950): Disable input method client, pid=1505
D/StatusBarManagerService(  950): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  950): Enable input method client, pid=6363
I/Adreno-EGL( 6337): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6337): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6337): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6337): Local Branch: 
I/Adreno-EGL( 6337): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6337): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6337):                  d74aa161a12b9c6fc6332151
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
D/PMS     (  950): releaseWL(2f58e17a): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  950): Displayed com.test.thalitest/.MainActivity: +896ms
W/XT9_C   ( 1380): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1380): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1380): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1380): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6363): Cannot call determinedVisibility() - never saw a connection for the pid: 6363
D/JsMessageQueue( 6363): Set native->JS mode to OnlineEventsBridgeMode
E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  950):  packet count Tx=152 Rx=297
I/CheckinRequestBuilder( 4230): Classify the device as Phone.
D/libc    ( 4230): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4230): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4230): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4230): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4230): [NET] android_getaddrinfo_proxy+
D/libc    ( 4230): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4230): [NET] android_getaddrinfo_proxy-, success
E/WifiDataStallTracker(  950): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  950): updateDataStallInfo: mDataStallTxRxSum={txSum=134 rxSum=123} preTxRxSum={txSum=133 rxSum=123}
D/WifiDataStallTracker(  950): updateDataStallInfo: OUT sent=1 mSentSinceLastRecv=1
D/WifiDataStallTracker(  950): onDataStallAlarm: Sent 1 pkts since last received, < watchdogTrigger=5
I/HtcModeClient( 3028): handler message = 4011
E/HtcModeClient( 3028): Check connection and retry 12 times.
D/libc    ( 4230): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4230): [NET] android_getaddrinfofornet-, err=8
D/jxcore_app_log( 6363): JniHelper::setJavaVM(0xab2988f8), pthread_self() = -1403253704
D/libc    ( 4230): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4230): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4230): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4230): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4230): Sending checkin request (8411 bytes)
I/chromium( 6363): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiStateMachine(  950): handleMessage: E msg.what=131155
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=7.0 bcn=0 [on:0 tx:0 rx:0 period:2288] from screen [on:0 period:-974098281] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=7.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-974098279] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950):  get link layer stats 0
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1324): environment dirty rate=13 [15][2][0]
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  950): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  950): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.61 txretriesrate=0.00 rxrate=10.00 userTriggerdPenalty0
E/WifiStateMachine(  950):  good link -> stuck count =0
E/WifiStateMachine(  950):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  950):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  950): RSSI current: 3 new: -63, 3
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  950): handleMessage: X
I/CheckinRequestBuilder( 4230): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  950): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4230): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1921): Explicit concurrent mark sweep GC freed 9662(497KB) AllocSpace objects, 3(252KB) LOS objects, 48% free, 4MB/8MB, paused 750us total 54.742ms
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4230): awaiting user notification for token,
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1220): reapply : com.google.android.gms 2 40
,I/CheckinRequestBuilder( 4230): Classify the device as Phone.
,I/CheckinTask( 4230): Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,I/CheckinService( 4230): Checking schedule, now: 1455019815324 next: 1455556647319
I/CheckinService( 4230): active receiver: disabled
,I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4230, uid=10024, userID:0
,D/PMS     (  950): releaseWL(1ce97be): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  950): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6437 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/PMS     (  950): releaseHCC(7ae6c6e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  950): releaseHCC(3561df0f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/PhoneMonitor( 6437): Register our PhoneStateListener,
,V/SetupWizard( 6437): Connected to Gservices successfully
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  950):  packet count Tx=168 Rx=310
D/WIFI_ICON( 1220): WifiActivity: 3,
E/WifiTrafficPoller(  950): notifying of data activity 3
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ChimeraCfgMgr( 4230): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PhoneMonitor( 6437): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/Kids    ( 4230): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
D/PhoneMonitor( 6437): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1921): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/jxcore-log( 6363): Initializing JXcore engine
W/jxcore-log( 6363): JXcore engine is ready
,W/jxcore-log( 6363): Starting JXcore engine
,W/jxcore-log( 6363): Platform android
W/jxcore-log( 6363): 
W/jxcore-log( 6363): Process ARCH arm
W/jxcore-log( 6363): 
,I/jxcore-log( 6363): JXcore Cordova bridge is ready!
I/jxcore-log( 6363): 
W/jxcore-log( 6363): JXcore engine is started
,E/jxcore  ( 6363): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6363): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6363): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PMS     (  950): acquireWL(2c53aceb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 950 1000 null
,W/PluginManager( 6363): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 44ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  950): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1505): [onResume]
I/FeedProviderManager( 1505): onResume
I/SocialFeedProvider( 1505): +onResume
,I/SocialFeedProvider( 1505): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1505): -onResume
,D/StatusBarManagerService(  950): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  950): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  950): hiding MENU key
,D/FindExtension( 1505): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1505): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  950): Disable input method client, pid=6363
D/StatusBarManagerService(  950): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
I/InputMethodManagerService(  950): Enable input method client, pid=1505
,W/IInputConnectionWrapper( 6363): reportFullscreenMode on inactive InputConnection
,D/PMS     (  950): releaseWL(2c53aceb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  950): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  950): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  950): hiding MENU key
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  950):  packet count Tx=168 Rx=311
D/WIFI_ICON( 1220): WifiActivity: 1
E/WifiTrafficPoller(  950): notifying of data activity 1
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/OpenGLRenderer( 1505): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1220): WifiActivity: 0
E/WifiTrafficPoller(  950):  packet count Tx=168 Rx=311
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  950): notifying of data activity 0
,E/WifiStateMachine(  950): handleMessage: E msg.what=131155,
E/WifiStateMachine(  950): processMsg: ConnectedState
,E/WifiStateMachine(  950):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.6, 0.0, 0.0  rx=10.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-974095259] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
,E/WifiStateMachine(  950):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.6, 0.0, 0.0  rx=10.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-974095258] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  950):  get link layer stats 0
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  950): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  950): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.30 txretriesrate=0.00 rxrate=7.00 userTriggerdPenalty0
,E/WifiStateMachine(  950):  good link -> stuck count =0
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  950):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  950):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  950): RSSI current: 3 new: -63, 3
E/WifiStateMachine(  950): handleMessage: X
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  950):  packet count Tx=168 Rx=311
,D/Process (  950): killProcessQuiet, pid=5815
,I/ActivityManager(  950): Killing 5815:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 5815
,D/Process (  950): killProcessQuiet, pid=5784
I/ActivityManager(  950): Killing 5784:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 5784
,D/Process (  950): killProcessQuiet, pid=5859
I/ActivityManager(  950): Killing 5859:com.htc.calendar/u0a10 (adj 15): empty #18
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 5859
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1220): WifiActivity: 3
E/WifiTrafficPoller(  950):  packet count Tx=170 Rx=313
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  950): notifying of data activity 3
,E/WifiDataStallTracker(  950): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  950): updateDataStallInfo: mDataStallTxRxSum={txSum=151 rxSum=137} preTxRxSum={txSum=134 rxSum=123}
,D/WifiDataStallTracker(  950): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  950): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/HtcModeClient( 3028): handler message = 4011,
,E/HtcModeClient( 3028): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3028): Don't start project servcice
D/HtcModeClient( 3028): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3028): connectState: CONNECTION_READY = false
,D/SilentMusic( 3028): call stop
D/HtcModeClient( 3028): close connection,
W/HtcModeClient( 3028): leaveProjectMode: It does not enter ProjectMode,
,W/CANMesgAgentLocalSocket( 3028): read the terminate packet, so break
,D/Process (  950): killProcessQuiet, pid=3028
I/ActivityManager(  950): Killing 3028:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 3028
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1220): WifiActivity: 1
E/WifiTrafficPoller(  950):  packet count Tx=170 Rx=314
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  950): notifying of data activity 1
,E/WifiStateMachine(  950): handleMessage: E msg.what=131155,
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=7.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-974092236] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=7.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-974092235] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950):  get link layer stats 0
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  950): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
,E/WifiStateMachine(  950): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.15 txretriesrate=0.00 rxrate=5.00 userTriggerdPenalty0
,E/WifiStateMachine(  950):  good link -> stuck count =0
E/WifiStateMachine(  950):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  950):  isHighRSSI       ---> score=61
E/WifiStateMachine(  950): handleMessage: X
D/WifiWatchdogStateMachine(  950): RSSI current: 3 new: -63, 3
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  950): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6463 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  950): acquireWL(21d44b19): PARTIAL_WAKE_LOCK  *alarm* 0x1 950 1000 WorkSource{10076}
V/AlarmManager(  950): sending alarm PendingIntent{49bc7de: PendingIntentRecord{20ededbf com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455019821255, Int=60000
D/PMS     (  950): releaseWL(21d44b19): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6463): SMSBackupAgentService started,
D/SMSBackup( 6463): Checking restore status
,D/SMSBackup( 6463): Restore complete,
D/SMSBackup( 6463): cancelCheckAlarm
,D/SMSBackup( 6463): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  950): killProcessQuiet, pid=5935
I/ActivityManager(  950): Killing 5935:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1220): WifiActivity: 0
E/WifiTrafficPoller(  950):  packet count Tx=170 Rx=314
E/WifiTrafficPoller(  950): notifying of data activity 0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  950): Recipient 5935
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  950):  packet count Tx=170 Rx=314
,W/SystemReader(  950): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1717): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/Prism.ItemManager( 1505): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1505): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1505): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
D/AccTypeManager( 1717): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  950): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6486 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
W/ResourcesManager(  950): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1717): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1445): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,E/ExternalAccountType( 1717): Unsupported attribute readOnly,
,W/ResourcesManager( 6486): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/PackageManager(  950): Unable to load service info ResolveInfo{32bc8fd8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  950): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  950): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  950): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  950): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  950): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  950): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  950): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  950): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  950): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  950): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  950): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  950): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  950): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  950): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  950): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  950): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1825): DISABLE
,I/BackupManagerService(  950): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1825): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,D/LocationProviderProxy(  950): applying state to connected service
D/PMS     (  950): acquireWL(36e9b53f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(36e9b53f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  950): applying state to connected service
,D/PMS     (  950): acquireWL(20c5a36): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(20c5a36): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(1e830d37): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  950): releaseWL(1e830d37): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6486): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6486): MmsConfig.loadMmsSettings
D/PMS     (  950): acquireWL(1b5d92a4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  950): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6516 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/art     (  950): Explicit concurrent mark sweep GC freed 30846(1751KB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 18MB/28MB, paused 1.488ms total 144.410ms,
D/PMS     (  950): releaseWL(1b5d92a4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6486, uid=10112, userID:0
,W/HtcWrapAdjustableCursorFactory( 6516): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,W/Settings( 6486): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 6516): onCreate,
,I/Babel_Crash( 6486): startup - clean
V/GetPrviateResource( 6516): GetPrviateResource
D/MmsCustomizationProvider( 6516): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 6516): GetPrviateResource
,D/MessageCustFlag( 6516): sense_version=6.0,
,D/BTAccessoryUtil( 6516): createReceiver
D/MmsCustomizationProvider( 6516): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 6486): deleted: false for 0
,D/BTAccessoryUtil( 6516): registerReceiver return intent = null
D/MessageCustFlag( 6516): sku_id=118
,D/HtcBuildUtils( 6516): getRATByHtcTelephonyCapability:1
W/SystemReader( 6516): Cannot find qct_8960_interface, use default value instead
,I/Babel_SMS( 6486): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 6486): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6486): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6486): MmsConfig.loadFromResources
,E/Babel_SMS( 6486): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6486): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6486, uid=10112, userID:0
,I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6486, uid=10112, userID:0
,I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6486, uid=10112, userID:0,
I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6486, uid=10112, userID:0
,I/PackageManager(  950):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6486, uid=10112, userID:0,
,D/PMS     (  950): acquireWL(1a7dbce6): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6486 10112 null,
,W/VideoCapabilities( 6486): Unrecognized profile 2130706433 for video/avc
,I/[PluginManager]RegisterService( 1591): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1591): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4230): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4230): Null package name or gms related package.  Ignoreing.
,D/PMS     (  950): acquireWL(29460240): PARTIAL_WAKE_LOCK  AsyncService 0x1 6054 10167 null,
,D/PMS     (  950): releaseWL(29460240): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  950): acquireWL(186abf1f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6054 10167 null,
D/PMS     (  950): acquireWL(1ca9026c): PARTIAL_WAKE_LOCK  Icing 0x1 4230 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(186abf1f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
I/Icing   ( 4230): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 5894): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  950): releaseWL(1ca9026c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/VideoCapabilities( 6486): Unsupported mime video/x-ms-wmv,
,W/Utils   ( 6486): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 6486): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6486): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6486): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6486): Unsupported mime video/x-ms-wmv
,I/UpdateIcingCorporaServi( 5894): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] ,
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  950):  packet count Tx=170 Rx=314
,I/VideoCapabilities( 6486): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6486): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6486): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6486): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6486): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 6486): onServiceConnected,
W/Babel   ( 6486): Attempted to change video mute state without an active call.,
,D/PMS     (  950): releaseWL(1a7dbce6): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null,
,W/ResourcesManager( 6486): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6486): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 6486): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6486): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6486): Installed default security provider GmsCore_OpenSSL
,E/WifiStateMachine(  950): handleMessage: E msg.what=131155,
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-974089215] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-974089214] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950):  get link layer stats 0
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  950): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  950): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.58 txretriesrate=0.00 rxrate=2.50 userTriggerdPenalty0
E/WifiStateMachine(  950):  good link -> stuck count =0
E/WifiStateMachine(  950):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  950):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  950): RSSI current: 3 new: -63, 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  950): handleMessage: X
,I/Prism.ItemManager( 1505): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1505): loadItems() com.htc.launcher.pageview.WidgetManager@32f069a4 +
I/Prism.WidgetManager( 1505): onLoadItems() +
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  950):  packet count Tx=170 Rx=314
,E/WifiDataStallTracker(  950): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  950): updateDataStallInfo: mDataStallTxRxSum={txSum=151 rxSum=137} preTxRxSum={txSum=151 rxSum=137},
D/WifiDataStallTracker(  950): updateDataStallInfo: NONE
D/WifiDataStallTracker(  950): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/Prism.WidgetManager( 1505): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1505): onLoadItems() -
I/Prism.ItemManager( 1505): loadItems() com.htc.launcher.pageview.WidgetManager@32f069a4 -
,D/PhoneApp( 1445): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1445): -- N1 =0
,D/PhoneApp( 1445): -- N2 =0
,D/PhoneApp( 1445): -- N3 =0
,D/Messaging( 6516): supportCMAS(SIE)/init? false/true,
,D/MmsConfig( 6516): networkCode: 
D/MessageCustFlag( 6516): sku_id=118,
,D/MmsConfig( 6516): SIE smsPri: null
D/MmsConfig( 6516): networkCode: 
,D/MmsConfig( 6516): packageName: com.htc.vvm.att does not exist,
,D/Messaging( 6516): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 6516): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6516): ,
D/MmsAsyncWorkHandler( 6516): HM tk = 20001
D/ReportIndicatorCache( 6516): MSG_QUERY_REPORTS >>
,D/SettingsManager( 6516): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3c395b7d
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1445): sku_id=118
,D/DraftCache( 6516): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 6516): [DraftCache/1] refresh
D/DraftCache( 6516): [DraftCache/161] DraftCache.constructor
D/DraftCache( 6516): [DraftCache/161] refresh
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/MmsSmsV2Provider( 1445):  slotId = -1000
,D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 6516): [DraftCache/161] rebuildCache,
,I/Messaging( 6516): mccmnc> 
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MmsConfig( 6516): networkCode: 
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,W/ContentService(  950): Observer android.database.IContentObserver$Stub$Proxy@3c8c20ed is already registered.
,W/ContentService(  950): Observer android.database.IContentObserver$Stub$Proxy@1e006b22 is already registered.,
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/Messaging( 6516): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/MmsSmsV2Provider( 1445):  slotId = -1000
D/MmsSmsV2Provider( 1445): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6516): ViewCache CreatePreloadOnlyConversationList
,D/Messaging( 6516): mNeedToUpdateDate2: false
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/Jerry   ( 1445): URI_DRAFT,
,D/DraftCache( 6516): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 6516): [DraftCache/161] rebuildCache time: 13
D/DraftCache( 6516): [DraftCache/161] rebuildCache
D/MessageCustFlag( 6516): sense_version=6.0
D/Jerry   ( 6516): start to preload cursor >>>>>>>
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/Jerry   ( 1445): URI_DRAFT
D/PhoneStorageUtil( 6516): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6516): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6516): createReceiver
,D/DraftCache( 6516): hasDraft() = false mNeedNotifyChange = false
,D/DraftCache( 6516): [DraftCache/161] rebuildCache time: 1
D/MmsAsyncWorkHandler( 6516): 
D/MmsAsyncWorkHandler( 6516): HM tk = 20002
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49,
D/MmsSmsV2Provider( 1445):  slotId = -1000
,D/TelephUtils( 1445): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
V/MmsProvider( 1445): Update uri=content://mms, match=0
V/MmsProvider( 1445): selection=st=129 AND m_type!=134
D/Messaging( 6516): Reset downloading state: 0
D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1445): sku_id=118
V/MmsSystemEventReceiver( 6516): TransactionService is going to be woken up.
,D/Messaging( 6516): ViewCache CreatePreload
D/Messaging( 6516): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 6516): 1-Creating TransactionService
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
,D/AccFlag ( 1445): sku_id=118
,D/Cust_MMSMS( 6516): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6516): def_index: 0,
,V/TransactionService( 6516): onStartCommand: 1
D/MsgPreferenceUtils( 6516): globalIndex = 1
D/MmsSystemEventReceiver( 6516): unRegisterForConnectionStateChanges
,V/TransactionService( 6516): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6516): Loading previous transactions.
E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/MsgPreferenceUtils( 6516): phone state: true
D/MsgPreferenceUtils( 6516): sd state: false
D/MsgPreferenceUtils( 6516): vIndex = 0
D/WIFI_ICON( 1220): WifiActivity: 1
E/WifiTrafficPoller(  950):  packet count Tx=170 Rx=315
E/WifiTrafficPoller(  950): notifying of data activity 1
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/TelephUtils( 1445): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1445): device_type: 1
,D/TransactionService( 6516): Force clearing mTransactionList
D/TransactionService( 6516): Force set service start id to 1
V/TransactionService( 6516): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6516): unRegisterForConnectionStateChanges
,V/TransactionService( 6516): Destroying TransactionService
D/TransactionService( 6516): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 6516): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/ActivityManager(  950): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{10422cf6 #7 A=.Prism U=0 sz=1}
W/PMS     (  950): mWirelessDisplayManager is null
,I/SensorManager(  950): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1c56187b
W/PMS     (  950): mWirelessDisplayManager is still null
,W/SensorService(  950): Following SensorService logs are not warning, just make sure they are printed,
I/PMS     (  950): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  950): disable: get sensor name = Accelerometer Sensor
I/PMS     (  950): Sleeping (uid 1000)...
W/SensorService(  950): pid=950, uid=1000
D/XAN-DPS (  950): prepareColorFade 1
W/SensorService(  950): Active sensors: size = 4
W/PMN     (  950): goingToSleep
W/SensorService(  950): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  950): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  950): CM36686 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  950): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  950): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1c56187b, eanble = 0, strlen(mName) = 91
W/SensorService(  950): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  950): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@39396645
W/SensorService(  950): Listener[1] = com.htc.smartdim.sensor_eye@cee8310
D/PMS     (  950): acquireWL(122448f7): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 950 1000 null
W/SensorService(  950): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1220): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/Adreno-EGL(  950): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  950): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  950): Build Date: 03/09/15 Mon
I/Adreno-EGL(  950): Local Branch: 
I/Adreno-EGL(  950): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  950): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  950):                  d74aa161a12b9c6fc6332151
,I/FeedHostManager( 1505): [onPause],
I/FeedProviderManager( 1505): onPause
,I/SocialFeedProvider( 1505): +onPause
W/PMN     (  950): goingToSleep done
I/SocialFeedProvider( 1505): -onPause
D/AlarmManager(  950): ACTION_SCREEN_ON
I/FeedHostManager( 1505): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@16ef5fcb
,I/AlarmManager(  950): [AlarmQueuing] recover blocked alarms,
I/AlarmManager(  950): [AlarmQueuing] done recovering
I/AlarmManager(  950): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  950): [AlarmQueuing] done EPS screen off alarm recovering
,I/ActivityManager(  950): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6582 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,W/HtcSystemUPManager(  950): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  950): releaseWL(122448f7): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null,
,E/WifiTrafficPoller(  950): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/WIFI_ICON( 1220): WifiActivity: 0,
E/WifiTrafficPoller(  950):  packet count Tx=170 Rx=315
E/WifiTrafficPoller(  950): notifying of data activity 0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  950): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  950): updateDataStallInfo: mDataStallTxRxSum={txSum=151 rxSum=137} preTxRxSum={txSum=151 rxSum=137},
D/WifiDataStallTracker(  950): updateDataStallInfo: NONE
D/WifiDataStallTracker(  950): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  950): handleMessage: E msg.what=131167
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  950): processMsg: ConnectModeState
E/WifiStateMachine(  950):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  950): processMsg: DriverStartedState
E/WifiStateMachine(  950):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
D/WifiDisplayAdapter(  950): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  950):     Client/Owner: Client
D/WifiDisplayAdapter(  950):     GroupId: 
D/WifiDisplayAdapter(  950):     Passphrase: 
D/WifiDisplayAdapter(  950):     SessionId: 0
D/WifiDisplayAdapter(  950):     IP Address: }
E/WifiStateMachine(  950): processMsg: SupplicantStartedState
E/WifiStateMachine(  950):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  950): processMsg: DefaultState
E/WifiStateMachine(  950):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  950):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1324): SET_SCREEN_ON:On
,I/wpa_supplicant( 1324): htc_wext_set_keepalive +
I/wpa_supplicant( 1324): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1324): getPrivFuncNum +,	
I/wpa_supplicant( 1324): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1324): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1324): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  950): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  950): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  950): handleScreenStateChanged Exit: true
E/WifiStateMachine(  950): handleMessage: X
E/WifiStateMachine(  950): handleMessage: E msg.what=131154
,E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SIGNAL_POLL'
,V/SRS_Proc(  405): ParamSet string: screen_state=on
E/audio_a2dp_hw(  405): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  950): handleMessage: E msg.what=155650
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
,D/NetworkPolicy(  950): updateScreenOn: false
V/NetworkPolicy(  950): updateIfacesLocked()
,D/NetworkManagementService(  950): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ResourcesManager( 6582): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/wpa_supplicant( 1324): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  950): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  950): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  950): handleMessage: X
E/WifiStateMachine(  950): handleMessage: E msg.what=131127
,E/WifiStateMachine(  950): processMsg: ConnectedState
,E/WifiStateMachine(  950):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  950): processMsg: ConnectModeState
E/WifiStateMachine(  950):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  950): handleMessage: X
E/WifiStateMachine(  950): handleMessage: E msg.what=131129
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  950): processMsg: ConnectModeState
E/WifiStateMachine(  950):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1324): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1324): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  950): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  950): WifiMonitor:wlan0 cnt=32 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  950): handleMessage: X
,D/GpsLocationProvider(  950): receive broadcast intent, action: android.intent.action.SCREEN_ON,
,D/XAN-DPS (  950): prepareColorFade done
,D/XAN-DPS (  950): setBrightness to 0
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/SensorManager(  950): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@39396645
I/DisplayManagerService(  950): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  950): Following SensorService logs are not warning, just make sure they are printed
,V/ActivityManager(  950): Display changed displayId=0
,W/SensorService(  950): disable: get sensor name = CM32181 Light sensor
D/DotMatrix( 1309): [EventService]  onDisplayChanged: 0
W/SensorService(  950): pid=950, uid=1000
W/SensorService(  950): Active sensors: size = 3
W/SensorService(  950): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  950): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  950): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  950): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@39396645, eanble = 0, strlen(mName) = 67
W/SensorService(  950): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  950): Listener[0] = com.htc.smartdim.sensor_eye@cee8310
W/SensorService(  950): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,I/CalendarProvider2( 6582): Created com.android.providers.calendar.CalendarAlarmManager@3fcbe727(com.htc.providers.calendar.HtcCalendarProvider@39697dd4)
,D/CalendarProvider2( 6582): wait start:true
,D/DotMatrix( 1309): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/IntentController( 1220): receive(android.intent.action.SCREEN_ON,1,false)
,D/PMS     (  950): acquireWL(1267a501): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(a2dbfa6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6582): wait end:false
,D/PMS     (  950): releaseWL(a2dbfa6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  950): releaseWL(1267a501): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AlarmManager(  950): ACTION_SCREEN_OFF
I/AlarmManager(  950): [AlarmQueuing] screen off now: 
,I/AlarmManager(  950): [AlarmQueuing] data connection: true
I/AlarmManager(  950): [AlarmQueuing] wifi connection: true
,I/ActivityManager(  950): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6611 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
E/WifiTrafficPoller(  950): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  950): stopDataStallAlarm 
E/WifiDataStallTracker(  950): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  950): handleMessage: E msg.what=131167
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  950): processMsg: ConnectModeState
E/WifiStateMachine(  950):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  950): processMsg: DriverStartedState
E/WifiStateMachine(  950):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  950): processMsg: SupplicantStartedState
E/WifiStateMachine(  950):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  950): processMsg: DefaultState
E/WifiStateMachine(  950):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  405): ParamSet string: screen_state=off
E/WifiStateMachine(  950):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  950): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1324): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1324): SET_SCREEN_ON:Off
I/wpa_supplicant( 1324): htc_wext_set_keepalive +
I/wpa_supplicant( 1324): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1324): getPrivFuncNum +	
I/wpa_supplicant( 1324): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1324): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1324): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1324): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1324): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  950): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  950): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  950):     Client/Owner: Client
D/WifiDisplayAdapter(  950):     GroupId: 
D/WifiDisplayAdapter(  950):     Passphrase: 
D/WifiDisplayAdapter(  950):     SessionId: 0
D/WifiDisplayAdapter(  950):     IP Address: }
E/audio_a2dp_hw(  405): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  950): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  950): handleScreenStateChanged Exit: false
E/WifiStateMachine(  950): handleMessage: X
E/WifiStateMachine(  950): handleMessage: E msg.what=131154
E/WifiStateMachine(  950): processMsg: ConnectedState
E/WifiStateMachine(  950):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiController(  950): handleMessage: E msg.what=155651
E/WifiStateMachine(  950):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
E/WifiStateMachine(  950): handleMessage: X
D/WifiController(  950): handleMessage: X
D/NetworkPolicy(  950): updateScreenOn: false
V/NetworkPolicy(  950): updateIfacesLocked()
D/GpsLocationProvider(  950): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/NetworkManagementService(  950): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SensorManager( 1220): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@13535481, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
W/SensorService(  950): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  950): enable: get sensor name = hTC Gesture Motion HIDI
W/SensorService(  950): pid=1220, uid=10041
W/SensorService(  950): Active sensors: size = 4
W/SensorService(  950): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  950): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  950): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  950): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  950): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@13535481, eanble = 1, strlen(mName) = 57
W/SensorService(  950): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  950): Listener[0] = com.htc.smartdim.sensor_eye@cee8310
W/SensorService(  950): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@13535481
W/SensorService(  950): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1309): [EventService] getTotalRam: 1842 Mb,
,I/IntentController( 1220): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1445): start background delete task...
,D/ContactMessageStore( 1445): size: 0 , 0
D/ContactMessageStore( 1445): Background delete complete
,D/PMS     (  950): acquireWL(628903d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(628903d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(7663032): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(7663032): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL false Token 13 num clients 6
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  950): Excessive delay in setPowerMode(): 287ms
D/PMS     (  950): Setting HAL interactive mode to false
,D/PMS     (  950): Setting HAL interactive mode to false done
D/PMS     (  950): Setting HAL auto-suspend mode to true
,D/PMS     (  950): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  950): screenObserver, isScreenOn=false,
D/StatusBarManagerService(  950): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  950): Disable input method client, pid=1505
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,W/HtcSystemUPManager(  950): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/PMS     (  950): acquireWL(3967ef00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
I/BatteryService(  950): n_update end
D/PMS     (  950): releaseWL(3967ef00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  950): updateBatteryInfo
D/HABCtrl (  950): TPE algorithm. remove timeout.
D/PMS     (  950): OOBE c monitor 11
D/NotificationService(  950): plugged=true pluggin=true
D/PMS     (  950): runPSCheck
D/HtcPowerSaver(  950): Checking...
I/HtcPowerSaver(  950): >> updateStatus
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
,D/UsbnetService(  950): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  950): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  950): << updateStatus
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  950): battery changed pluggedType: 2
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/WifiController(  950): handleMessage: E msg.what=155652
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
,D/NfcService( 1466): ScreenObserver: OFF,
I/InputManager(  950): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/NfcService( 1466): applyRouting - 0
I/IntentController( 1220): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PowerUsageList:PowerUsageHelper( 6611): MY_DEBUG = false
D/PMS     (  950): acquireWL(23431d7e): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1466 1027 null
,D/NfcService( 1466): applyRouting -2
D/NfcService( 1466): applyRouting
D/NfcService( 1466): Ignore this applyRouting...
D/PMS     (  950): releaseWL(23431d7e): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/RemoteViews( 1220): setHTCTheme(com.htc.updater,true,33751145),
,D/SmartSyncUtils( 6611): isEpsOn(), nState = 0
,I/RemoteViews( 1220): apply : com.htc.updater 2 20 2 36
,D/PMS     (  950): acquireWL(40422df): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6611 1000 null
,D/PowerUI ( 1220): closing low battery warning: level=100
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
I/ClockController( 1220): stop clock update:screen off
,W/ContextImpl(  950): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  950): Init customizeScreenOffDelayClass error
D/PMS     (  950): releaseWL(40422df): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6611): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6611): isEpsOn(), nState = 0
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  950): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  950): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@cee8310
W/SensorService(  950): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  950): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  950): pid=950, uid=1000
W/SensorService(  950): Active sensors: size = 3
W/SensorService(  950): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  950): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  950): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  950): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@cee8310, eanble = 0, strlen(mName) = 35
W/SensorService(  950): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  950): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@13535481
W/SensorService(  950): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  950): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  950): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  950): pid=950, uid=1000,
W/SensorService(  950): Active sensors: size = 2
W/SensorService(  950): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  950): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  950): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@cee8310, eanble = 0, strlen(mName) = 35
W/SensorService(  950): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  950): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@13535481
,W/SensorService(  950): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  950): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@cee8310,
,E/ActivityThread(  950): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1bdcde09 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  950): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1bdcde09 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  950): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  950): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  950): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  950): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  950): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  950): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  950): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  950): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  950): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  950): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  950): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  950): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  950): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  950): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  950): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  950): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  950): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  950): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  950): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  950): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6645 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/PowerUsageList:PowerUsageHelper( 6611): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6611): gen(), null == sipper.uidObj, userId = 0,
,D/SmartSyncUtils( 6611): getMobilePolicyEnabled, result = true
I/ActivityManager(  950): Killing 6211:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  950): killProcessQuiet, pid=6211
,D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  950): New client listening to asynchronous messages
E/WifiTrafficPoller(  950): ADD_CLIENT: 7
,I/ActivityManager(  950): Recipient 6211
,D/PowerUsageList:PowerUsageHelper( 6611): MY_DEBUG = false
,E/WifiTrafficPoller(  950): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,E/WifiStateMachine(  950): handleMessage: E msg.what=131155
E/WifiStateMachine(  950): processMsg: ConnectedState
,E/WifiStateMachine(  950):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-974086197] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-974086195] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950): handleMessage: X
,D/Process (  950): killProcessQuiet, pid=6235,
I/ActivityManager(  950): Killing 6235:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CalendarProvider2( 6582): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6582): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  950): Recipient 6235
,I/ActivityManager(  950): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6670 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  950): killProcessQuiet, pid=6023
,I/ActivityManager(  950): Killing 6023:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  950): releaseWL(3ed37ed2): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  950): Recipient 6023
,W/ResourcesManager( 6670): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6670): onCreate
,D/ProviderChangeReceiver( 6670): ---------------------------------------------------
,D/ProviderChangeReceiver( 6670): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/ActivityManager(  950): Killing 6263:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  950): killProcessQuiet, pid=6263
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6670): start to updateAlertNotification!
,I/ActivityManager(  950): Recipient 6263
,D/HtcAlertService( 6670): No fired or scheduled alerts
,D/HtcAlertUtils( 6670): -- cancelReminderNotification --
,D/HtcAlertUtils( 6670): broadcastExistReminder!
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  950): killProcessQuiet, pid=5435
I/ActivityManager(  950): Killing 5435:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 5435
,D/Process (  950): killProcessQuiet, pid=5461
I/ActivityManager(  950): Killing 5461:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 5461
,E/WifiStateMachine(  950): handleMessage: E msg.what=131155
E/WifiStateMachine(  950): processMsg: ConnectedState
,E/WifiStateMachine(  950):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2016] from screen [on:0 period:-974084179] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950): processMsg: L2ConnectedState
E/WifiStateMachine(  950):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-974084176] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  950): handleMessage: X
,D/HtcUPManager( 1220): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  950): DATA_MONITOR_POLL false Token 3
,E/WifiDataStallTracker(  950): DATA_MONITOR_POLL false Token 3
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Process (  950): killProcessQuiet, pid=5609
I/ActivityManager(  950): Killing 5609:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 5609,
,D/ContactMessageStore( 1445): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1445): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  950): acquireWL(e6f938a): PARTIAL_WAKE_LOCK  *alarm* 0x1 950 1000 WorkSource{10024}
,V/AlarmManager(  950): sending alarm PendingIntent{b320dfb: PendingIntentRecord{16a2d071 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141211, Int=0
V/AlarmManager(  950): sending alarm PendingIntent{273b5e56: PendingIntentRecord{17898ed7 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=112411, Int=0,
,D/libc    (  950): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  950): releaseWL(e6f938a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/libc    (  950): [NET] android_getaddrinfofornet-, err=8
D/libc    (  950): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  950): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  950): [NET] android_getaddrinfo_proxy+
D/libc    (  950): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  950): [NET] android_getaddrinfo_proxy-, success
,D/AlarmManager(  950): Ignore time set to 1455019856572 in setTime(); too close to current time 1455019856585,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  950): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  950): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  950): acquireWL(6183c4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 950 1000 null
,D/libc    (  950): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  950): [NET] android_getaddrinfofornet-, err=8
D/libc    (  950): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  950): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  950): [NET] android_getaddrinfo_proxy+
D/libc    (  950): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  950): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  950): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  950): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  950): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  950): [reportHTCStatus] eventMask = 3 , status = 0,
D/PMS     (  950): acquireWL(bd51830): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 950 1000 null
D/GpsLocationProvider(  950): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  950): releaseWL(6183c4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  950):  [handleDownloadXtraData]inject done.
D/PMS     (  950): releaseWL(bd51830): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  950): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  950): acquireWL(1c3a1ca9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
I/BatteryService(  950): n_update end
D/PMS     (  950): releaseWL(1c3a1ca9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  950): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  950): updateBatteryInfo
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/NotificationService(  950): plugged=true pluggin=true
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  950): runPSCheck
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  950): Checking...
D/WifiController(  950): handleMessage: E msg.what=155652
I/HtcPowerSaver(  950): >> updateStatus
D/WifiController(  950): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): battery changed pluggedType: 2
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  950): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1445): switchBindHtcMsgCursor: null,
,D/PMS     (  950): acquireWL(d2fe22e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 950 1000 WorkSource{1000}
V/AlarmManager(  950): sending alarm PendingIntent{ef4e8dc: PendingIntentRecord{33625de5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=144725, Int=0
,V/AlarmManager(  950): sending alarm PendingIntent{11e181cf: PendingIntentRecord{146eda65 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455019883152, Int=0
V/AlarmManager(  950): sending alarm PendingIntent{8dbf33a: PendingIntentRecord{229e6beb android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=201639, Int=0,
V/AlarmManager(  950): sending alarm PendingIntent{2517bd48: PendingIntentRecord{3477b7e1 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455019870510, Int=1800000
V/AlarmManager(  950): sending alarm PendingIntent{2a060906: PendingIntentRecord{3bf5dbc7 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191865, Int=0
D/PMS     (  950): acquireWL(338f65f4): PARTIAL_WAKE_LOCK  *backup* 0x1 950 1000 null
,W/BackupManagerService(  950): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  950): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  950): releaseWL(338f65f4): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
D/PMS     (  950): acquireWL(33d6f11d): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4230 10024 WorkSource{10024 com.google.android.gms}
D/WeatherUtility( 1220): Weather sync is On
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/PMS     (  950): releaseWL(d2fe22e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/PMS     (  950): acquireWL(326a6d63): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(2236ed60): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4230 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(33d6f11d): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(2c0d7f8c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4230): Aggregate from 1455019812838 (log), 1455018070345 (data)
,D/PMS     (  950): releaseWL(326a6d63): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  950): releaseWL(2236ed60): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(2c0d7f8c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(31e8bfb6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(31e8bfb6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(274744b7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(274744b7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  950): acquireWL(cd23424): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(393b5b8d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10176 com.google.android.youtube},
,I/ActivityManager(  950): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6698 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/PMS     (  950): acquireWL(b817553): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms},
,I/art     (  950): Explicit concurrent mark sweep GC freed 31471(1749KB) AllocSpace objects, 4(1064KB) LOS objects, 33% free, 18MB/28MB, paused 1.762ms total 199.859ms
W/ResourcesManager( 6698): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6698): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  950): releaseWL(cd23424): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1921): Vacuum at: now=1455019917433 tag=VacuumService
,D/PMS     (  950): releaseWL(b817553): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  950): acquireWL(110f2389): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,V/JNIHelp ( 6698): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  950): releaseWL(110f2389): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  950): acquireWL(253c0f8e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,W/System  ( 6698): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6698): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  950): releaseWL(253c0f8e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/art     ( 6698): Suspending all threads took: 18.075ms
,W/ResourcesManager( 6698): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6698): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/cutils-trace( 6730): Error opening trace file: Permission denied (13),
,I/dex2oat ( 6730): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1132582205.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads1132582205.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6730): dex2oat: override thread count:4
,I/dex2oat ( 6730): dex2oat took 49.986ms (threads: 4),
,E/YouTube MDX( 6698): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 6698): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
D/libc    ( 6698): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  950): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 6698): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  950): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 6698): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  950): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 6698): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  950): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 6698): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 6698): Found 10024
,D/VoldConnector(  950): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 6698): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/PMS     (  950): acquireWL(3e225116): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(3e225116): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(393b5b8d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10176 com.google.android.youtube}
,D/PMS     (  950): acquireWL(176a68a2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  950): releaseWL(176a68a2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(337c1933): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): acquireWL(2bf674f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(337c1933): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1921): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  950): Killing 6437:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  950): killProcessQuiet, pid=6437
,D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Uploader( 1921): No account for auth token provided
,D/libc    ( 6698): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 6698): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6698): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6698): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6698): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6698): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6698): [NET] android_getaddrinfo_proxy-, success,
,D/libc    ( 6698): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 6698): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  950): Recipient 6437,
,D/libc    ( 6698): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6698): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1921): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1921): [NET] android_getaddrinfo_proxy+
D/libc    ( 1921): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1921): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1921): No account for auth token provided,
,W/Uploader( 1921):  no longer exists, so no auth token.,
,W/Uploader( 1921): No account for auth token provided,
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1921): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1921): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1921): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1921): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1921): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1921): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263),
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1921): 	at com.google.android.gms.gcm.am.run(SourceFile:135),
I/RemoteViews( 1220): reapply : com.google.android.gms 3 40
,W/Uploader( 1921): No account for auth token provided,
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1921): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1921): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1921): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1921): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1921): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1921): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1921): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1921): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1220): reapply : com.google.android.gms 3 40
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  950): releaseWL(2bf674f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  950): acquireWL(28fddd4d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(28fddd4d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  950): acquireWL(412e002): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(412e002): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1591): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2d34267e
,I/ActivityManager(  950): Killing 6363:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  950): killProcessQuiet, pid=6363
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 6363
,E/InputEventReceiver( 1380): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{7983c39 uid 10366 pid 6363} (c)'
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  950): acquireWL(3fd62d13): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  950): n_update end
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  950): releaseWL(3fd62d13): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
D/PowerUI ( 1220): closing low battery warning: level=100
D/HtcPowerSaver(  950): updateBatteryInfo
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  950): BroadcastReceiver::onReceive+
D/NotificationService(  950): plugged=true pluggin=true
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/PMS     (  950): runPSCheck
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  950): Checking...
D/UsbnetService(  950): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  950): >> updateStatus
,D/WifiController(  950): handleMessage: E msg.what=155652
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): processMsg: StaEnabledState
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  950): processMsg: DefaultState
,I/HtcPowerSaver(  950): << updateStatus
D/WifiController(  950): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1324): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  950): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  950): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/wpa_supplicant( 1324): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  950): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
,D/PMS     (  950): acquireWL(1f9f2b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
,I/BatteryService(  950): n_update end
D/UsbnetService(  950): BroadcastReceiver::onReceive+
D/PMS     (  950): releaseWL(1f9f2b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  950): plugged=true pluggin=true,
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  950): updateBatteryInfo
D/WifiController(  950): handleMessage: E msg.what=155652
D/PMS     (  950): runPSCheck
D/WifiController(  950): processMsg: DeviceActiveState
,D/HtcPowerSaver(  950): Checking...
D/WifiController(  950): processMsg: StaEnabledState
I/HtcPowerSaver(  950): >> updateStatus
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): handleMessage: X
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  950): << updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  950): acquireWL(5d80149): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
I/BatteryService(  950): n_update end
D/PMS     (  950): releaseWL(5d80149): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  950): updateBatteryInfo
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
D/NotificationService(  950): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  950): BroadcastReceiver::onReceive+
,D/PMS     (  950): runPSCheck
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  950): Checking...
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  950): >> updateStatus
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): handleMessage: E msg.what=155652
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
,I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  950): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  950): acquireWL(14d2fa4e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 950 1000 WorkSource{1000}
V/AlarmManager(  950): sending alarm PendingIntent{ef4e8dc: PendingIntentRecord{33625de5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=204725, Int=0
,V/AlarmManager(  950): sending alarm PendingIntent{a53ac7c: PendingIntentRecord{8166905 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1455020073301, Int=0,
,D/PMS     (  950): releaseWL(14d2fa4e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1220): Weather sync is On,
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,I/art     ( 1505): Background sticky concurrent mark sweep GC freed 66922(4MB) AllocSpace objects, 3(288KB) LOS objects, 12% free, 32MB/36MB, paused 5.904ms total 50.175ms,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1921): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1921): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1921): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1921): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1921): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1220): reapply : com.google.android.gms 1 40
W/GLSActivity( 1921): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1921): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1921): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1921): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1921): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1921): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1921): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5982): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5982): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5982): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5982): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5982): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5982): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5982): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5982): Ignoring header User-Agent because its value was null.
,D/libc    ( 5982): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5982): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5982): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5982): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5982): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5982): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5982): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
D/PMS     (  950): acquireWL(38b42a5f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  950): n_update end
D/PMS     (  950): releaseWL(38b42a5f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  950): BroadcastReceiver::onReceive+
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  950): plugged=true pluggin=true
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  950): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  950): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  950): Checking...
D/WifiController(  950): handleMessage: E msg.what=155652
I/HtcPowerSaver(  950): >> updateStatus
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  950): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  950): acquireWL(2e192cac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null,
D/UsbnetService(  950): BroadcastReceiver::onReceive+
I/BatteryService(  950): n_update end
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/PMS     (  950): releaseWL(2e192cac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  950): plugged=true pluggin=true
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): handleMessage: E msg.what=155652
D/HtcPowerSaver(  950): updateBatteryInfo
D/WifiController(  950): processMsg: DeviceActiveState
D/PMS     (  950): runPSCheck
D/WifiController(  950): processMsg: StaEnabledState
D/HtcPowerSaver(  950): Checking...
D/WifiController(  950): processMsg: DefaultState
I/HtcPowerSaver(  950): >> updateStatus
D/WifiController(  950): handleMessage: X
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  950): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  950): acquireWL(55c9d75): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
I/BatteryService(  950): n_update end
D/PMS     (  950): releaseWL(55c9d75): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  950): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  950): runPSCheck
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  950): Checking...
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  950): >> updateStatus
,D/PowerUI ( 1220): closing low battery warning: level=100,
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  950): << updateStatus
D/NotificationService(  950): plugged=true pluggin=true
D/UsbnetService(  950): BroadcastReceiver::onReceive+
,D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/WifiController(  950): battery changed pluggedType: 2
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/WifiController(  950): handleMessage: E msg.what=155652
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  950): acquireWL(3de6e10a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
I/BatteryService(  950): n_update end
D/PMS     (  950): releaseWL(3de6e10a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  950): updateBatteryInfo
D/PMS     (  950): runPSCheck
D/HtcPowerSaver(  950): Checking...
I/HtcPowerSaver(  950): >> updateStatus
,D/PowerUI ( 1220): closing low battery warning: level=100
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  950): BroadcastReceiver::onReceive+,
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  950): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  950): << updateStatus
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  950): plugged=true pluggin=true
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): handleMessage: E msg.what=155652
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
,D/WifiController(  950): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1445): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1445): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1445): sku_id=118
D/ContactMessageStore( 1445): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1445): start background delete task...
D/ContactMessageStore( 1445): size: 0 , 0,
D/ContactMessageStore( 1445): Background delete complete
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  950): acquireWL(b9b0d7b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
D/UsbnetService(  950): BroadcastReceiver::onReceive+
I/BatteryService(  950): n_update end
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/PMS     (  950): releaseWL(b9b0d7b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  950): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  950): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  950): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  950): Checking...
I/HtcPowerSaver(  950): >> updateStatus
,D/WifiController(  950): handleMessage: E msg.what=155652
D/WifiController(  950): processMsg: DeviceActiveState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  950): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  950): acquireWL(17426798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
I/BatteryService(  950): n_update end
,D/PMS     (  950): releaseWL(17426798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  950): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  950): updateBatteryInfo
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/NotificationService(  950): plugged=true pluggin=true
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  950): runPSCheck
D/UsbnetService(  950): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  950): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  950): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  950): << updateStatus
D/WifiController(  950): handleMessage: E msg.what=155652
,D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  950): acquireWL(1a669bf1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
,I/BatteryService(  950): n_update end,
D/PMS     (  950): releaseWL(1a669bf1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  950): updateBatteryInfo
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): closing low battery warning: level=100
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  950): plugged=true pluggin=true
,D/UsbnetService(  950): BroadcastReceiver::onReceive+
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/PMS     (  950): runPSCheck
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  950): Checking...
D/UsbnetService(  950): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  950): >> updateStatus
D/WifiController(  950): handleMessage: E msg.what=155652
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X,
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  950): << updateStatus
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5957): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5957): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5957): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5957): Cust_ConnectToPC   : spcsc>false
D/        ( 5957): Cust_ConnectToPC   : IPT>true
,D/        ( 5957): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5957): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5957): Index of the first 1 = -1
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
W/ContextImpl( 5957): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5957): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5957): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SmartNS_Utility( 5957): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5957): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5957): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5957): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5957): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/PMS     (  950): acquireWL(32430657): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 950 1000 WorkSource{1000}
V/AlarmManager(  950): sending alarm PendingIntent{ef4e8dc: PendingIntentRecord{33625de5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=384726, Int=0
V/AlarmManager(  950): sending alarm PendingIntent{1b495d4b: PendingIntentRecord{2babc328 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805657, Int=0
V/AlarmManager(  950): sending alarm PendingIntent{10c26544: PendingIntentRecord{3438062d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937839, Int=0
,I/ActivityManager(  950): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6794 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  950): sending alarm PendingIntent{18a8762: PendingIntentRecord{3507b0f3 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1455020339774, Int=0
,D/PMS     (  950): acquireWL(3b2291b0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1921 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  950): releaseWL(3b2291b0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  950): releaseWL(32430657): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1220): Weather sync is On
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/PMS     (  950): acquireWL(143bd829): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1921 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1921): Message class com.google.f.a.a.i
,D/PMS     (  950): releaseWL(143bd829): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,E/cutils-trace( 6816): Error opening trace file: Permission denied (13),
,I/dex2oat ( 6816): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6816): dex2oat: override thread count:4
,I/dex2oat ( 6816): dex2oat took 683.503ms (threads: 4),
,I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6794): ApplicationMonitor {11ad8bbe}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6794): PnsModel {25853279}: update(): Update registration caused by: alarm,
,I/PushClient( 6794): PnsConfigModel {3ad20404}: <init>(): Use dm-client for provisioning.
,W/System.err( 6794): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6794): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6794): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6794): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  950): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6823 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6823): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6823 dbg=false s=true
,I/DeviceManagement( 6823): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6823): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6823): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6823): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6823): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@6caa340] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6823): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6823): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6823): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6823): SessionStateController: Checking invariants...,
,I/bt-btm  ( 2921): Received oneshot timer event complete
D/PMS     (  950): acquireWL(19bc3347): PARTIAL_WAKE_LOCK  *alarm* 0x1 950 1000 WorkSource{1002}
I/bt-btm  ( 2921): btm_ble_timeout
V/AlarmManager(  950): sending alarm PendingIntent{3caba774: PendingIntentRecord{19d3d49d com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=939386, Int=0
I/bt-btm  ( 2921): btm_gen_resolvable_private_addr
,D/PMS     (  950): releaseWL(19bc3347): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
,D/PMS     (  950): acquireWL(18678d12): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 2921 1002 null,
,D/bt-btm  ( 2921): btm_ble_rand_enc_complete,
I/bt-btm  ( 2921): btm_gen_resolve_paddr_low
D/bt-smp  ( 2921): smp_encrypt_data
W/bt-smp  ( 2921): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 2921): Plain text(LSB ~ MSB) = f9 09 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2921): Encrypted text(LSB ~ MSB) = 2d b8 04 2a c5 ad ab 7e b4 cf ed 28 ca bd 9e bc 
I/bt-btm  ( 2921): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 2921): Stopping oneshot timer
D/bt-btm  ( 2921): Starting oneshot timer type:103 timeout:900s,
,I/DeviceManagement( 6823): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6823): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6823): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6823): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@6caa340]
,I/DeviceManagement( 6823): WorkflowService: Stopping workflow service
,D/Process (  950): killProcessQuiet, pid=6337
I/ActivityManager(  950): Killing 6337:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6794): PnsModel {25853279}: update(): Start updating since the registration has expired.
,W/PushClient( 6794): GCMRegistrator {2dfc0507}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.
W/PushClient( 6794):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6794):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6794):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6794):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6794):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 6794):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6794):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6794):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6794):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6794):   
,I/ActivityManager(  950): Recipient 6337
,D/GCM     ( 1921): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER,
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 1921): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1921): [NET] android_getaddrinfo_proxy+
D/libc    ( 1921): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1921): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1921): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1921): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6794): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 4,
D/libc    ( 6794): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6794): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6794): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6794): [NET] android_getaddrinfo_proxy+
D/libc    ( 6794): [NET] android_getaddrinfo_proxy get netid:0,
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6794): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  950): releaseWL(18678d12): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/PushClient( 6794): PnsModel {25853279}: update(): Update registration succeeded.,
,D/Process (  950): killProcessQuiet, pid=6463
,I/ActivityManager(  950): Killing 6463:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  950): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  950): Recipient 6463
,D/PMS     (  950): acquireWL(3ce3ac6a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 950 1000 WorkSource{1000}
,V/AlarmManager(  950): sending alarm PendingIntent{ef4e8dc: PendingIntentRecord{33625de5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=984726, Int=0
,V/AlarmManager(  950): sending alarm PendingIntent{f74e55b: PendingIntentRecord{2ad3d1ad com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455020683901, Int=0
,W/ContextImpl( 6611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6611): MY_DEBUG = false,
,D/PowerUsageService( 6611): repeat time = 1455021600028
D/WeatherUtility( 1220): Weather sync is On
D/PMS     (  950): releaseWL(3ce3ac6a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,I/PowerUsageList:PowerUsageHelper( 6611): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6611): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  950): acquireWL(165ce6d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null
I/BatteryService(  950): n_update end
,D/PMS     (  950): releaseWL(165ce6d1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  950): updateBatteryInfo,
,D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  950): BroadcastReceiver::onReceive+
D/NotificationService(  950): plugged=true pluggin=true
D/UsbnetService(  950): onReceive BATTERY_CHANGED
,D/PMS     (  950): runPSCheck
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  950): Checking...
D/UsbnetService(  950): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  950): >> updateStatus
,D/WifiController(  950): handleMessage: E msg.what=155652
D/WifiController(  950): battery changed pluggedType: 2
D/WifiController(  950): processMsg: DeviceActiveState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  950): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/SmartSyncUtils( 6611): isEpsOn(), nState = 0
D/PMS     (  950): acquireWL(2a882536): PARTIAL_WAKE_LOCK  *alarm* 0x1 950 1000 WorkSource{1000}
,V/AlarmManager(  950): sending alarm PendingIntent{15127c37: PendingIntentRecord{2441d5a4 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455020726643, Int=0
D/PMS     (  950): releaseWL(2a882536): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  950): acquireWL(1ff81f0d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6611 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6611): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6611): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6611): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6611): SettingOnTime = 1455084000000, randomSettingOnTime = 1455082018000
D/SmartSyncScreenOnOffTimeReceiver( 6611): SettingOffTime = 1455062400000, randomSettingOffTime = 1455069335000
,D/SmartSyncScreenOnOffTimeReceiver( 6611): bDayMode = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6611): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6611): bNightModeTurnOffOnce = false
,D/PMS     (  950): releaseWL(1ff81f0d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  950): acquireWL(7295ec2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 950 1000 null,
I/BatteryService(  950): n_update end
D/PMS     (  950): releaseWL(7295ec2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  950): updateBatteryInfo
D/NotificationService(  950): plugged=true pluggin=true
D/PMS     (  950): runPSCheck
D/HtcPowerSaver(  950): Checking...
I/HtcPowerSaver(  950): >> updateStatus
,D/UsbnetService(  950): BroadcastReceiver::onReceive+
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  950): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  950):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  950): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  950): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  950): << updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  950): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  950): handleMessage: E msg.what=155652
D/WifiController(  950): processMsg: DeviceActiveState
D/WifiController(  950): processMsg: StaEnabledState
D/WifiController(  950): processMsg: DefaultState
D/WifiController(  950): handleMessage: X
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 2921): Disconnected process message: 10, size: 0
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  950): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
