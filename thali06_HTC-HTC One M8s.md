#### Test 58380500055030c_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  938):  packet count Tx=199 Rx=269
--------- beginning of system
D/PMS     (  938): acquireWL(1135c8c): PARTIAL_WAKE_LOCK  *alarm* 0x1 938 1000 WorkSource{10072}
V/AlarmManager(  938): sending alarm PendingIntent{3bb93fd5: PendingIntentRecord{131143ea com.android.vending startService}}, i=null, t=0, cnt=1, w=1454970784382, Int=0
V/AlarmManager(  938): sending alarm PendingIntent{120766db: PendingIntentRecord{16dfb578 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454970785524, Int=536832000
V/CheckinService( 4440): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
V/AlarmManager(  938): sending alarm PendingIntent{b26a564: PendingIntentRecord{153113cd android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454970778854, Int=20000
D/PMS     (  938): acquireWL(395b0451): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4440 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  938): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
E/WifiStateMachine(  938): handleMessage: E msg.what=131143
D/PMS     (  938): releaseWL(1135c8c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:119 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.1 list=2412 [on:0 tx:0 rx:0 period:1666] from screen [on:0 period:-1023127790]
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:119 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.1 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1023127789]
E/WifiStateMachine(  938): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.44 rxSuccessRate=1.05 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-63
E/WifiStateMachine(  938): WifiStateMachine CMD_START_SCAN with age=58687 interval=60000 maxinterval=300000
E/WifiStateMachine(  938): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  938): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  938): has c0:ff:d4:d3:aa:48 freq=2412 age=1673 ?=true
E/WifiStateMachine(  938): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1411): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1411): wpa_supplicant_scan enter
D/wpa_supplicant( 1411): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1411): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1411): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1411): WPS:  * Request Type
D/wpa_supplicant( 1411): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1411): WPS:  * UUID-E
D/wpa_supplicant( 1411): WPS:  * Primary Device Type
D/wpa_supplicant( 1411): WPS:  * RF Bands (3)
D/wpa_supplicant( 1411): WPS:  * Association State
D/wpa_supplicant( 1411): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1411): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1411): WPS:  * Manufacturer
D/wpa_supplicant( 1411): WPS:  * Model Name
D/wpa_supplicant( 1411): WPS:  * Model Number
D/wpa_supplicant( 1411): WPS:  * Device Name
D/wpa_supplicant( 1411): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1411): P2P: * P2P IE header
D/wpa_supplicant( 1411): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1411): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1411): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1411): wlan0: Add radio work 'scan'@0x556afd4860
D/wpa_supplicant( 1411): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1411): wlan0: Starting radio work 'scan'@0x556afd4860 after 0.000046 second wait
D/wpa_supplicant( 1411): wlan0: nl80211: scan request
D/wpa_supplicant( 1411): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1411): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1411): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1411): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1411): wlan0: Own scan request started a scan in 0.000136 seconds
I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  938): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  938): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  938): [1,454,970,785,559 ms] noteScanstart no scan source
E/WifiStateMachine(  938): handleMessage: X
D/PMS     (  938): acquireWL(380b95b7): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4440 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  938): releaseWL(395b0451): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4440): Checking schedule, now: 1454970785582 next: 1454970785524
I/CheckinService( 4440): active receiver: enabled
I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4440, uid=10024, userID:0
I/CheckinService( 4440): Preparing to send checkin request
I/EventLogService( 4440): Accumulating logs since 1454970749014
D/wpa_supplicant( 1411): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1411): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1411): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1411): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1411): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1411): wlan0: Scan completed in 0.073488 seconds
D/wpa_supplicant( 1411): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1411): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1411): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1411): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1411): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1411): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
D/wpa_supplicant( 1411): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1411): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1411): wlan0: Scan-only results received
D/wpa_supplicant( 1411): wlan0: Radio work 'scan'@0x556afd4860 done in 0.074559 seconds
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  938): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  938): handleMessage: E msg.what=147461
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  938): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1411): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  938): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  938): [1,454,970,785,638 ms] noteScanEnd no scan source
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1411): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  938): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@1130d168 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  938): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  938): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  938): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  938): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  938):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-63 freq=2412
E/WifiAutoJoinController (  938): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  938): ageScanResultsOut delay 40000 size 3 now 1454970785641
E/WifiAutoJoinController (  938): newSupplicantResults size=3 known=1 true
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1411): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  938): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  938): ssid=NG700
E/WifiAutoJoinController (  938): id=0
E/WifiAutoJoinController (  938): mode=station
E/WifiAutoJoinController (  938): pairwise_cipher=CCMP
E/WifiAutoJoinController (  938): group_cipher=CCMP
E/WifiAutoJoinController (  938): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  938): wpa_state=COMPLETED
E/WifiAutoJoinController (  938): ip_address=192.168.1.130
E/WifiAutoJoinController (  938): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  938): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  938): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  938): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  938): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController (  938): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  938): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-63 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  938): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  938): Done attemptAutoJoin status=0
E/WifiConfigStore(  938):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  938): handleMessage: X
I/CheckinRequestBuilder( 4440): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  938): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4440): Failed to find provider info for com.google.android.wearable.settings
I/GLSUser ( 1925): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1925): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1925): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1925): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/cutils-trace( 6512): Error opening trace file: Permission denied (13)
W/CheckinRequestBuilder( 4440): awaiting user notification for token
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1224): reapply : com.google.android.gms 2 40
I/ActivityManager(  938): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6529 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/CustomizationManager( 6512): ====startRecUseTime====
D/htc.customization.log.level( 6512):  is 
W/CustomizationLogLevel( 6512): Level value is invalid, use default level 2
W/ResourcesManager( 6529): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6529): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6529): VM with version 2.1.0 has multidex support
I/MultiDex( 6529): install
I/MultiDex( 6529): VM has multidex support, MultiDex support library is disabled.
D/CustomizationManager( 6512):  Read ACC file spent 0.044 (s)
D/CIDMapFileReader( 6512): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6512): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6512): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6512): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6512): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6512): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6512): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6512): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6512): Parsing tag category name = system
I/CustomizationCIDLoader( 6512): Parsing tag category name = application
I/CustomizationCIDLoader( 6512): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6512): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6512): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6512): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6512): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6512): add string-array item, value = 42507
I/CustomizationCIDLoader( 6512): add string-array item, value = 21902
I/CustomizationCIDLoader( 6512): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6512): add string-array item, value = 23420
I/CustomizationCIDLoader( 6512): add string-array item, value = 22299
I/CustomizationCIDLoader( 6512): add string-array item, value = 24002
I/CustomizationCIDLoader( 6512): add string-array item, value = 23210
I/CustomizationCIDLoader( 6512): add string-array item, value = 23205
I/CustomizationCIDLoader( 6512): add string-array item, value = 23806
I/CustomizationCIDLoader( 6512): add string-array item, value = 23430
I/CustomizationCIDLoader( 6512): add string-array item, value = 23408
I/CustomizationCIDLoader( 6512): add string-array item, value = 27205
I/CustomizationCIDLoader( 6512): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6512): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6512):  Read CID file spent 0.091 (s)
D/CustomizationManager( 6512):  All configurations done spent 0.091 (s)
V/JNIHelp ( 6529): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 6019): [602] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6019): [1] 5.onFinished: Installation state replication succeeded.
W/ActivityThread( 6529): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6529): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29550978: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6529): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1925): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  938): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6512 on display 0
D/PMS     (  938): acquireHCC(1f75aa7): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 938 1000 null
D/PMS     (  938): acquireHCC(381aab54): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 938 1000 null
W/asset   (  938): Copying FileAsset 0x559a9ee2e0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  938): acquireWL(fb4fa43): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 938 1000 null
I/AnimationUtil(  938): isHTCRecent(ThaliTest/Recent screens.)/5
D/AuthorizationBluetoothService( 1925): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/FeedHostManager( 1495): [onPause]
I/FeedProviderManager( 1495): onPause
V/GmsCoreStatsServiceLauncher( 4440): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SocialFeedProvider( 1495): +onPause
I/SocialFeedProvider( 1495): -onPause
I/FeedHostManager( 1495): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@fad05
W/HtcSystemUPManager(  938): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  938): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6554 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/WearableService( 5730): callingUid 10024, callindPid: 5730
E/MDM     ( 1840): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/StatusBarManagerService(  938): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  938): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  938): hiding MENU key
W/asset   ( 6554): Copying FileAsset 0xabfbdda8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1495): [trimMemory] 20
,I/WVCdm   (  448): CdmEngine::OpenSession
I/WVCdm   (  448): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  448): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  448): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  448): Service_Initialize: starts!
D/QSEECOMAPI: (  448): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  448): App is not loaded in QSEE
E/QSEECOMAPI: (  448): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  448): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  448): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  448): App is not loaded in QSEE
I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4440, uid=10024, userID:0
D/QSEECOMAPI: (  448): Loaded image: APP id = 8
D/DrmWidevineDash(  448): Service_Initialize: ends! returns 0
D/LocationInitializer( 4440): Restart initialization of location
D/QSAPPSVER(  448): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  448): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  448): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d06000
E/DrmWidevineDash(  448): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d06000
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  578): got the req here! ret=0
D/DrmLibTime(  578): command id, time_cmd_id = 770
D/DrmLibTime(  578): time_getutcsec starts!
D/DrmLibTime(  578): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  578): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  578): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  578): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  578): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  578): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  578): QSEE Time Listener: Retrieved Android system time: 1454970786
D/DrmLibTime(  578): time_getutcsec returns 0, sec = 1454970786; nsec = 0
D/DrmLibTime(  578): time_getutcsec finished! 
D/DrmLibTime(  578): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  578): before calling ioctl to read the next time_cmd
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): hlos api version =  9
D/DrmWidevineDash(  448): tz api version =  9
D/DrmWidevineDash(  448): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  448): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/WebViewFactory( 6554): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  448): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  448): OEMCrypto_OpenSession: starts! SID=0xf3f1b928
D/DrmWidevineDash(  448): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  448): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_GetRandom: starts! randomData=0xab7371a0, dataLength=8
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab683ca0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  448): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  448): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  448): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  448): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  448): OEMCrypto_GetDeviceID: starts! deviceID=0xab6d6e60, idLength=0xff91ae38
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  448): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  448): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_GetHDCPCapability: starts!, current = 0xff91ae4e, maximum = 0xff91ae4f
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): hlos api version =  9
D/DrmWidevineDash(  448): tz api version =  9
D/DrmWidevineDash(  448): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  448): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xff91aebc
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  448): PrepareKeyRequest: nonce=896858070
D/DrmWidevineDash(  448): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab68b9b8
D/DrmWidevineDash(  448): message_length=1611, signature=0xab7787a8, signature_length=0xff91ae1c
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/LibraryLoader( 6554): Time to load native libraries: 16 ms (timestamps 6106-6122)
I/LibraryLoader( 6554): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6554): Binding Chromium to main looper Looper (main, tid 1) {2ce2b4ef}
I/LibraryLoader( 6554): Expected native library version number "",actual native library version number ""
I/chromium( 6554): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6554): Initializing chromium process, singleProcess=true
E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1224): WifiActivity: 1
E/WifiTrafficPoller(  938):  packet count Tx=199 Rx=270
E/WifiTrafficPoller(  938): notifying of data activity 1
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/art     ( 6554): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6554): ApplicationContext is null in ApplicationStatus
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  448): CdmEngine::CloseSession
D/DrmWidevineDash(  448): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  448): L3 Terminate.
D/DrmWidevineDash(  448): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): Service_Uninitialize: starts!
D/QSEECOMAPI: (  448): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  448): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  448): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  448): OEMCrypto_Terminate: ends! returns 0
W/chromium( 6554): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6554): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6554): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6554): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6554): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6554): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6554): Local Branch: 
I/Adreno-EGL( 6554): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6554): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6554):                  d74aa161a12b9c6fc6332151
W/System.err(  938): java.lang.Throwable: stack dump
D/BluetoothManagerService(  938): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  938): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5af7cab:true
W/System.err(  938): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  938): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  938): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  938): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6554): 836889576: getState(). Returning 12
E/cutils-trace( 6598): Error opening trace file: Permission denied (13)
I/dex2oat ( 6598): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6598): dex2oat: override thread count:4
I/art     ( 1925): Explicit concurrent mark sweep GC freed 10297(535KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 944us total 52.633ms
I/dex2oat ( 6598): dex2oat took 56.190ms (threads: 4)
W/art     ( 6554): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6554): onDetachedFromWindow called when already detached. Ignoring
I/Adreno-EGL( 6529): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6529): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6529): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6529): Local Branch: 
I/Adreno-EGL( 6529): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6529): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6529):                  d74aa161a12b9c6fc6332151
D/SystemWebViewEngine( 6554): CordovaWebView is running on device made by: HTC
W/art     ( 6554): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6554): Attempt to remove local handle scope entry from IRT, ignoring
I/Adreno-EGL( 6529): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6529): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6529): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6529): Local Branch: 
I/Adreno-EGL( 6529): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6529): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6529):                  d74aa161a12b9c6fc6332151
W/chromium( 6554): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6554): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
E/WifiStateMachine(  938): handleMessage: E msg.what=131155
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:1328] from screen [on:0 period:-1023126456] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1023126456] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  938):  get link layer stats 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1411): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  938): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  938): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.22 txretriesrate=0.00 rxrate=1.03 userTriggerdPenalty0
E/WifiStateMachine(  938):  good link -> stuck count =0
E/WifiStateMachine(  938):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  938):  isHighRSSI       ---> score=61
E/WifiStateMachine(  938): handleMessage: X
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/WVCdm   (  448): CdmEngine::OpenSession
I/WVCdm   (  448): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  448): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  448): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  448): Service_Initialize: starts!
D/QSEECOMAPI: (  448): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  448): App is not loaded in QSEE
E/QSEECOMAPI: (  448): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  448): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  448): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  448): App is not loaded in QSEE
I/InputMethodManager( 6554): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@65c1f18, mServedView=org.apache.cordova.engine.SystemWebView{2b42bd71 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@37894756
D/QSEECOMAPI: (  448): Loaded image: APP id = 9
D/DrmWidevineDash(  448): Service_Initialize: ends! returns 0
I/InputMethodManagerService(  938): Disable input method client, pid=1495
D/StatusBarManagerService(  938): swetImeWindowStatus vis=0 backDisposition=0
D/QSAPPSVER(  448): qsapps_get_capabilities: Capability from secure side: 0x0
I/InputMethodManagerService(  938): Enable input method client, pid=6554
D/QSAPPSVER(  448): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  448): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d06000
E/DrmWidevineDash(  448): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4d06000
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  578): got the req here! ret=0
D/DrmLibTime(  578): command id, time_cmd_id = 770
D/DrmLibTime(  578): time_getutcsec starts!
D/DrmLibTime(  578): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  578): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  578): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  578): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  578): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  578): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  578): QSEE Time Listener: Retrieved Android system time: 1454970786
D/DrmLibTime(  578): time_getutcsec returns 0, sec = 1454970786; nsec = 0
D/DrmLibTime(  578): time_getutcsec finished! 
D/DrmLibTime(  578): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  578): before calling ioctl to read the next time_cmd
E/QC-time-services(  474): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
I/ActivityManager(  938): Displayed com.test.thalitest/.MainActivity: +867ms
D/DrmWidevineDash(  448): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): hlos api version =  9
D/DrmWidevineDash(  448): tz api version =  9
D/DrmWidevineDash(  448): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  448): OEMCrypto_IsKeyboxValid: starts!
D/PMS     (  938): releaseWL(fb4fa43): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/PhoneStatusBar( 1224): setImeWindowStatus(false,false)
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  448): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  448): OEMCrypto_OpenSession: starts! SID=0xf4e32928
D/DrmWidevineDash(  448): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  448): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_GetRandom: starts! randomData=0xab7374c8, dataLength=8
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab683ca0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/XT9_C   ( 1381): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1381): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1381): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1381): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  448): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  448): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  448): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  448): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  448): OEMCrypto_GetDeviceID: starts! deviceID=0xab6d6e80, idLength=0xf4f326f8
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/BindingManager( 6554): Cannot call determinedVisibility() - never saw a connection for the pid: 6554
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  448): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  448): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4f3270e, maximum = 0xf4f3270f
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  448): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): hlos api version =  9
D/DrmWidevineDash(  448): tz api version =  9
D/DrmWidevineDash(  448): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  448): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4f3277c
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  448): PrepareKeyRequest: nonce=3788785242
D/DrmWidevineDash(  448): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab68b9b8
D/DrmWidevineDash(  448): message_length=1646, signature=0xab7787a8, signature_length=0xf4f326dc
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/JsMessageQueue( 6554): Set native->JS mode to OnlineEventsBridgeMode
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  448): CdmEngine::CloseSession
D/DrmWidevineDash(  448): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  448): L3 Terminate.
D/DrmWidevineDash(  448): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  448): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  448): Service_Uninitialize: starts!
D/QSEECOMAPI: (  448): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  448): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  448): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  448): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 4440): Classify the device as Phone.
D/libc    ( 4440): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4440): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4440): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4440): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4440): [NET] android_getaddrinfo_proxy+
D/libc    ( 4440): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  428): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  428): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  428): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4440): [NET] android_getaddrinfo_proxy-, success
D/jxcore_app_log( 6554): JniHelper::setJavaVM(0xaae518f8), pthread_self() = -1407622872
D/libc    ( 4440): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4440): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4440): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4440): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4440): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4440): [NET] android_getaddrinfofornet-, err=8
I/chromium( 6554): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/CheckinTask( 4440): Sending checkin request (8444 bytes)
E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  938):  packet count Tx=214 Rx=280
E/WifiTrafficPoller(  938): notifying of data activity 3
D/WIFI_ICON( 1224): WifiActivity: 3
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/CheckinRequestBuilder( 4440): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  938): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4440): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  938): releaseHCC(1f75aa7): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  938): releaseHCC(381aab54): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/art     (  938): Explicit concurrent mark sweep GC freed 30752(1922KB) AllocSpace objects, 5(164KB) LOS objects, 33% free, 16MB/25MB, paused 1.599ms total 157.012ms,
,I/GLSUser ( 1925): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1925): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1925): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1925): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4440): awaiting user notification for token,
,I/RemoteViews( 1224): reapply : com.google.android.gms 3 40
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/CheckinRequestBuilder( 4440): Classify the device as Phone.,
,I/CheckinTask( 4440): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4440): Checking schedule, now: 1454970788287 next: 1455507620273,
I/CheckinService( 4440): active receiver: disabled
I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4440, uid=10024, userID:0
,D/PMS     (  938): releaseWL(380b95b7): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  938): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6633 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,W/jxcore-log( 6554): Initializing JXcore engine,
W/jxcore-log( 6554): JXcore engine is ready
,D/PhoneMonitor( 6633): Register our PhoneStateListener
,V/SetupWizard( 6633): Connected to Gservices successfully
,W/jxcore-log( 6554): Starting JXcore engine
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4440): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 6633): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6633): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1925): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  938):  packet count Tx=215 Rx=284
,W/jxcore-log( 6554): Platform android,
W/jxcore-log( 6554): 
W/jxcore-log( 6554): Process ARCH arm
W/jxcore-log( 6554): 
,E/WifiDataStallTracker(  938): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  938): updateDataStallInfo: mDataStallTxRxSum={txSum=195 rxSum=176} preTxRxSum={txSum=179 rxSum=163}
D/WifiDataStallTracker(  938): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  938): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/jxcore-log( 6554): JXcore Cordova bridge is ready!,
I/jxcore-log( 6554): 
W/jxcore-log( 6554): JXcore engine is started
,I/jxcore-log( 6554): Toggling radios to true,
I/jxcore-log( 6554): 
,D/BluetoothAdapter( 6554): enable(): BT is already enabled..!,
,D/WifiManager( 6554): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  938): MONITOR_LOG
D/WifiService(  938): setWifiEnabled: true pid=6554, uid=10366
W/Settings:Agent(  938): name: wifi_on
D/WifiService(  938): New client listening to asynchronous messages
,W/Settings:Agent(  938): value: 2
E/WifiService(  938): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  938): >> traceCallingStack()
I/WifiService(  938): isSprintWifiRestricted(): false
W/Settings:Agent(  938): Process.myPid(): 938
I/WifiService(  938): isMdmWifiRestricted(): false
W/Settings:Agent(  938): Process.myTid(): 965
W/Settings:Agent(  938): Process.myUid(): 1000
,W/Settings:Agent(  938): 
W/Settings:Agent(  938): 
E/WifiTrafficPoller(  938): ADD_CLIENT: 7
W/System.err(  938): java.lang.Throwable: stack dump
,W/System.err(  938): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  938): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  938): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64),
W/System.err(  938): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  938): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  938): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  938): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  938): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  938): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
,W/System.err(  938): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  938): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  938): 
W/Settings:Agent(  938): << traceCallingStack(): 24(ms)
D/WifiController(  938): handleMessage: E msg.what=155656
D/WifiManager( 6554): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  938): processMsg: DeviceActiveState
D/WifiController(  938): processMsg: StaEnabledState
,D/WifiController(  938): handleMessage: X
D/WifiManager( 6554): reconnect: Base Package Name=com.test.thalitest, uid=10366
,E/WifiStateMachine(  938): handleMessage: E msg.what=131145
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
,D/wpa_supplicant( 1411): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1411): wlan0: Cancelling scan request
D/wpa_supplicant( 1411): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1411): TDLS: Tear down peers
D/wpa_supplicant( 1411): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6554): Radios toggled
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): My device name is: HTC-HTC One M8s
I/jxcore-log( 6554): 
,D/wpa_supplicant( 1411): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1411): wlan0: Deauthentication notification
D/wpa_supplicant( 1411): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1411): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1411): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1411): enter disconnect check
I/wpa_supplicant( 1411): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1411): wlan0: Auto connect disabled: do not try to re-connect
,D/wpa_supplicant( 1411): wlan0: Ignore connection failure indication since interface has been put into disconnected state
,D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/Tethering(  938): interfaceLinkStateChanged wlan0, false
D/Tethering(  938): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  938): interfaceLinkStateChanged wlan0, false
D/Tethering(  938): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  938): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  938): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  938): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiMonitor(  938): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  938): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  938): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  938): sendTetherStateChangedBroadcast 0, 0, 0,
D/UsbDeviceManager(  938): [USBNET] bCheckSuppFunc: cdc_network
,D/UsbnetService(  938): BroadcastReceiver::onReceive+
D/PMS     (  938): acquireWL(1bb8d2b2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 938 1000 null
D/UsbnetService(  938): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
D/UsbnetService(  938): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1411): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1411): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1411): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1411): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1411): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x556aff1f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 1411):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1411): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1411): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1411): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1411): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1411): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1411): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1411): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1411): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1411): EAPOL: External notification - EAP success=0
D/WifiP2pService(  938): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1411): wlan0: State: DISCONNECTED -> DISCONNECTED
D/WifiP2pService(  938): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1411): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1411): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1411): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1411): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1411): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1411): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1411): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1411): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1411): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  938): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  938): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  938): handleMessage: new destination call exit/enter
E/WifiStateMachine(  938): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  938): invokeExitMethods: ConnectedState
E/WifiStateMachine(  938): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  938): release()
E/WifiStateMachine(  938): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  938): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  938): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  938): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  938): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  938): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  938): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  938): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1411): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1411): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1411): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SAVE_CO,NFIG'
D/wpa_supplicant( 1411): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1411): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1411): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  938): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1411): Power_Mode_Type mode = 0
I/wpa_supplicant( 1411): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  938): setDhcpActive: false
D/PMS     (  938): releaseWL(1bb8d2b2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/Netd    (  428): ifc_reset_connections failed on iface wlan0 for address 192.168.1.130/24 (Unknown error -1)
V/NetworkPolicy(  938): updateNetworkEnabledLocked()
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
V/NetworkPolicy(  938): updateNotificationsLocked()
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  938): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  938): setDetailed state send new extra info<unknown ssid>
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  938): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  938): NetworkAgent != null
V/NetworkPolicy(  938): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  938):  packet count Tx=215 Rx=284
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  938): notifying of data activity 0
D/WIFI_ICON( 1224): WifiActivity: 0
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/TetherSettings( 5994): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/        ( 5994): Cust_ConnectToPC   : Internet_Sharing>true
D/ConnectivityService(  938): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/        ( 5994): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5994): Cust_ConnectToPC   : spcsc>false
D/        ( 5994): Cust_ConnectToPC   : IPT>true
D/        ( 5994): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  938): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  938): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  938): QCOM Debug skip set_network part for security concern!
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1411): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1411): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1411): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WifiDataStallTracker(  938): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  938): stopDataStallAlarm 
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  938): ENABLE_DATA_MONITOR_POLL false Token 1
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/wpa_supplicant( 1411): wlan0: Control interface command 'SAVE_CONFIG'
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
D/wpa_supplicant( 1411): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1411): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1411): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  938): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  938): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  938): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  938):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  938): Start Disconnecting Watchdog 1
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=131146
E/WifiStateMachine(  938): processMsg: DisconnectingState
W/Settings( 5994): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 13
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
E/SmartNS_Utility( 5994): hasRemovableStorageSlot: true
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 5994): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5994): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  938):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  938):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1411): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1411): wlan0: Selecting BSS from priority group 641
D/wpa_supplicant( 1411): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-53 wps
D/wpa_supplicant( 1411): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1411): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1411): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-63 wps
D/wpa_supplicant( 1411): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1411): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1411): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1411):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1411): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1411): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x556aff3c00  current_ssid=0x0
D/wpa_supplicant( 1411): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1411): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1411): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1411): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1411): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1411): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1411): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1411): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1411): wlan0: Add radio work 'connect'@0x556afd4860
D/wpa_supplicant( 1411): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1411): wlan0: Starting radio work 'connect'@0x556afd4860 after 0.000115 second wait
I/wpa_supplicant( 1411): check if in concurrent case
I/wpa_supplicant( 1411): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  938): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=33 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1411): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1411): wlan0: Cancelling scan request
D/wpa_supplicant( 1411): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1411): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1411): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1411): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1411): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1411): RSN: PMKSA cache search - network_ctx=0x556aff3c00 try_opportunistic=0
D/wpa_supplicant( 1411): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1411): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1411): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1411): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1411): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1411): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1411): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1411): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1411): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1411): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): wlan0: State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1411): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1411): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1411): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1411): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1411): nl80211: Unsubscribe mgmt frames handle 0x888888dde277b989 (mode change)
D/wpa_supplicant( 1411): nl80211: Subscribe to mgmt frames with non-AP handle 0x556aff3100
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=0104
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=040a
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=040b
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=040c
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=040d
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=090a
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=090b
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=090c
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=090d
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=0409506f9a09
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=7f506f9a09
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=0801
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=040e
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=06
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=0a07
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=0a11
D/wpa_supplicant( 1411): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x556aff3100 match=0a1a
D/wpa_supplicant( 1411): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1411):   * bssid=c0:ff:d4:d3:aa:48
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1411):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411):   * freq=2412
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1411):   * freq_hint=2412
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1411):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1411):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1411):   * WPA Versions 0x2
D/wpa_supplicant( 1411):   * pairwise=0xfac04
D/wpa_supplicant( 1411):   * group=0xfac04
D/wpa_supplicant( 1411):   * akm=0xfac02
D/wpa_supplicant( 1411):   * Auth Type 0
D/wpa_supplicant( 1411): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x556aff3c3a
D/wpa_supplicant( 1411): nl80211: Connect request send successfully
D/wpa_supplicant( 1411): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1411): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1411): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1411): EAPOL: External notification - portControl=Auto
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  938): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  938): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=147460
E/WifiStateMachine(  938): processMsg: DisconnectingState
E/WifiStateMachine(  938):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=98879
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=98879
E/WifiStateMachine(  938): ConnectModeState: Network connection lost 
E/WifiStateMachine(  938): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  938): handleMessage: new destination call exit/enter
E/WifiStateMachine(  938): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  938): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  938): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  938): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  938): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  938): DisconnectedState call setCountryCode()
E/WifiStateMachine(  938):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1411): Ongoing scan action - reject new request
E/WifiStateMachine(  938): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
W/ContextImpl( 5994): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=131101
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiStateMachine(  938):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
I/SmartNS_Utility( 5994): setISNotification
E/WifiStateMachine(  938):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  938): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  938): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  938): handleMessage: X
D/SmartNS_Utility( 5994): usb_cable_connect = 1
E/WifiStateMachine(  938): handleMessage: E msg.what=147462
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiStateMachine(  938):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=98884  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  938): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  938): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=98885  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/SmartNS_Utility( 5994): usb_denied = 0
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=131212
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiStateMachine(  938):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
I/SmartNS_PSService( 5994): usb notificaiton:true
,E/WifiStateMachine(  938):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  938):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  938): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=131212
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiStateMachine(  938):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  938): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  938): handleMessage: X
D/WifiNetworkAgent(  938): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  938): handleMessage: E msg.what=131213
E/WifiStateMachine(  938): processMsg: DisconnectedState
I/ActionCombine( 5994): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
E/WifiStateMachine(  938):  DisconnectedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=98896
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=98897
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=98898
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=98898
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=147462
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiStateMachine(  938):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=98899  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  938): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  938): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  938): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  938): NetworkAgent == null
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  938): processMsg: ConnectModeState
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  938):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=98903  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  938): handleMessage: X
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 14
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/SmartNS_Utility( 5994): usb_cable_connect = 1
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/SmartNS_Utility( 5994): usb_denied = 0
I/SmartNS_PSService( 5994): usb notificaiton:true
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/QuickSettingWifi( 1224): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
I/RemoteViews( 1224): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5994): Tethered state change:false isNSOpening:false
D/ConnectivityService(  938): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/ConnectivityService(  938): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  938): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  938): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityManager.CallbackHandler( 1224): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  938): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  938): Removing idletimer
D/WIFI    (  938):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  938): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
I/SecurityController( 1224): onLost 100
E/WifiStateMachine(  938): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  938): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  938):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  938): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): Disconnected - quitting
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:17
,I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:0
,I/RemoteViews( 1224): reapply : com.android.settings 1 36
,I/ActivityManager(  938): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6666 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
D/WISPrService( 5994): >>>>>WISPrService start isConnected = true<<<<<
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/PMS     (  938): acquireWL(1a0d9580): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 938 1000 null,
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/Tethering(  938): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/CSLegacyTypeTracker(  938): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false,
D/Tethering(  938): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  938): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  938): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy(  938): ensureActiveMobilePolicyLocked()
D/PMS     (  938): acquireWL(1c55d7b9): PARTIAL_WAKE_LOCK  NetworkStats 0x1 938 1000 null
D/DATA_ICON( 1224): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  938): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
,V/NetworkPolicy(  938): updateNetworkEnabledLocked()
V/NetworkPolicy(  938): updateIfacesLocked()
V/NetworkPolicy(  938): updateNotificationsLocked()
D/NetworkManagementService(  938): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiTrafficPoller(  938): ADD_CLIENT: 8
D/WifiService(  938): New client listening to asynchronous messages
D/DATA_ICON( 1224): dataConnected: false/false
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/PMS     (  938): releaseWL(1c55d7b9): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  938): updateNetworkEnabledLocked()
,V/NetworkPolicy(  938): updateNotificationsLocked()
E/WifiStateMachine(  938): handleMessage: E msg.what=131131
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiStateMachine(  938):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  938): handleMessage: X
,W/WISPrService( 5994): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 5994): trigger connection
D/WISPrService( 5994): continue
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
D/wpa_supplicant( 1411): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1411): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1411): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1411): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1411): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1411): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1411): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1411): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1411): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1411): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1411): nl80211: Connect event
D/wpa_supplicant( 1411): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1411): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1411): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1411): wlan0: Association info event
D/wpa_supplicant( 1411): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): wlan0: freq=2412 MHz
D/wpa_supplicant( 1411): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1411): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1411): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1411): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1411): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1411): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1411): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1411): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1411): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1411): TDLS: Remove peers on association
D/wpa_supplicant( 1411): EAPOL: External notification - portEnabled=0
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1411): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1411): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1411): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1411): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1411): EAPOL: enable timer tick
D/wpa_supplicant( 1411): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1411): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1411): wlan0: Cancelling scan request
I/wpa_supplicant( 1411): htc_wext_set_keepalive +
I/wpa_supplicant( 1411): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1411): getPrivFuncNum +	
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1411): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1411): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/H,TCRequest(  938): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1411): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1411): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1411): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1411): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1411): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1411): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1411):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1411):   key_nonce - hexdump(len=32): 53 2b c2 9a 74 2f da ed 14 ce a9 86 cc c1 e1 95 6f aa 11 33 41 5a cb 2a 15 9d 43 0e 2b 27 25 38
D/wpa_supplicant( 1411):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1411):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1411):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1411):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1411): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1411): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1411): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  938): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/WifiStateMachine(  938): handleMessage: E msg.what=147462
D/WifiMonitor(  938): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  938): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  938): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  938): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  938): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  938):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=98980  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  938): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  938): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  938): setDetailed state send new extra info0x
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1411): WPA: Renewed SNonce - hexdump(len=32): a8 23 c0 78 19 09 d8 2c 03 25 a7 d0 51 c2 4f 6c 61 bc 1a 27 72 d9 0a 9c ed b4 8c 04 3c 67 76 b1
D/wpa_supplicant( 1411): WPA: Nonce1 - hexdump(len=32): a8 23 c0 78 19 09 d8 2c 03 25 a7 d0 51 c2 4f 6c 61 bc 1a 27 72 d9 0a 9c ed b4 8c 04 3c 67 76 b1
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1411): WPA: Nonce2 - hexdump(len=32): 53 2b c2 9a 74 2f da ed 14 ce a9 86 cc c1 e1 95 6f aa 11 33 41 5a cb 2a 15 9d 43 0e 2b 27 25 38
D/wpa_supplicant( 1411): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1411): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1411): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1411): wlan0: WPA: Sending EAPOL-Key 2/4,
D/wpa_supplicant( 1411): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1411): WPA: Derived Key MIC - hexdump(len=16): cb 43 45 6d 59 0e ff 3f c2 68 0a 2a a1 a5 06 ef
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/Tethering(  938): interfaceLinkStateChanged wlan0, false
D/Tethering(  938): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/Tethering(  938): interfaceLinkStateChanged wlan0, false
D/Tethering(  938): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
D/WISPrService( 5994): start DataConnection
D/HTCRequest(  938): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  938): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  938): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  938): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  938): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1411): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1411): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1411): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1411): wlan0:   key_length=16 key_data_length=56
D/Tethering(  938): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1411):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/Tethering(  938): interfaceStatusChanged wlan0, false
D/UsbDeviceManager(  938): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1411):   key_nonce - hexdump(len=32): 53 2b c2 9a 74 2f da ed 14 ce a9 86 cc c1 e1 95 6f aa 11 33 41 5a cb 2a 15 9d 43 0e 2b 27 25 38
D/PMS     (  938): acquireWL(d989498): PARTIAL_WAKE_LOCK  NetworkStats 0x1 938 1000 null
D/wpa_supplicant( 1411):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1411):   key_rsc - hexdump(len=8): f1 6f 00 00 00 00 00 00
D/wpa_supplicant( 1411):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1411):   key_mic - hexdump(len=16): 7f 53 3c b3 d9 0b eb 0d 75 9b d4 cc 36 0d 3c 0a
D/wpa_supplicant( 1411): RSN: encrypted key data - hexdump(len=56): 0e 5d 96 28 25 68 f8 54 2b 71 eb 68 c6 e5 60 31 5a 23 9a f8 8a 58 d3 be 81 7d 8a d6 f8 5f 6c 71 ...
D/libc    ( 5994): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/wpa_supplicant( 1411): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1411): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1411): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1411): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 3e 04 ...
D/wpa_supplicant( 1411): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1411): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1411): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1411): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1411): WPA: Derived Key MIC - hexdump(len=16): 33 1b 08 70 85 17 3e 3a 20 a7 32 6e 2b 98 f5 81
D/wpa_supplicant( 1411): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1411): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x556aff4390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1411): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1411): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1411):    addr=c0:ff:d4:d3:aa:48
D/libc    ( 5994): [NET] android_getaddrinfofornet-, err=8
D/wpa_supplicant( 1411): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1411): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1411): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1411): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1411): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1411): WPA: RSC - hexdump(len=6): f1 6f 00 00 00 00
D/wpa_supplicant( 1411): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x556005de68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1411): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1411): nl80211: KEY_SEQ - hexdump(len=6): f1 6f 00 00 00 00
D/wpa_supplicant( 1411):    broadcast key
D/Tethering(  938): interfaceLinkStateChanged wlan0, true
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/Tethering(  938): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1411): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  938): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
V/Tethering(  938): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1411): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1411): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1411): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1411): wlan0: Radio work 'connect'@0x556afd4860 done in 0.122914 seconds
I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor(  938): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
I/wpa_supplicant( 1411): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/libc    ( 5994): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5994): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5994): [NET] android_getaddrinfo_proxy+
E/WifiStateMachine(  938):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=98981  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/libc    ( 5994): [NET] android_getaddrinfo_proxy get netid:0
E/WifiStateMachine(  938): handleMessage: X
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  938): handleMessage: E msg.what=147500
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/wpa_supplicant( 1411): wlan0: Connect to SSID: NG700
D/libc    (  428): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/wpa_supplicant( 1411): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1411): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
E/WifiStateMachine(  938):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
D/libc    (  428): [NET] _dns_getaddrinfo+, netid:0, mark:917504
E/WifiStateMachine(  938):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  938): Enter handleAssociatedWithEvent
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateMachine(  938): Associated
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 1411): set send_ind_to_ndc = 0
I/wpa_supplicant( 1411): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1411): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1411): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1411): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1411): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1411): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1411): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1411): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1411): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1411): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1411): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1411): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1411): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/libc    (  428): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  428): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5994): [NET] android_getaddrinfo_proxy-, NODATA
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  938): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor(  938): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  938): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  938): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/UsbnetService(  938): BroadcastReceiver::onReceive+
D/WifiMonitor(  938): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=40 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  938): interfaceLinkStateChanged wlan0, true
D/UsbnetService(  938): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  938): BroadcastReceiver::onReceive-
D/Tethering(  938): interfaceStatusChanged wlan0, true
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/PMS     (  938): releaseWL(d989498): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiMonitor(  938): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor(  938): Event [IFNAME=wlan0 Connect to SSID: NG700]
D/WifiStateMachine(  938): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=42 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  938): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  938): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  938): Exit handleAssociatedWithEvent
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=147462
E/WifiStateMachine(  938): processMsg: DisconnectedState
D/WifiMonitor(  938): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  938):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=99001  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  938): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  938): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  938): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938): NetworkAgent == null
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=99012  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  938): handleMessage: X
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  938): updateNetworkEnabledLocked()
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 18
V/NetworkPolicy(  938): updateNotificationsLocked()
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: FOUR_WAY_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938): handleMessage: E msg.what=147462
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiStateMachine(  938):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=99018  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  938): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  938): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  938): processMsg: ConnectModeState
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: FOUR_WAY_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=99019  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=131101
E/WifiStateMachine(  938): processMsg: DisconnectedState
E/WifiStateMachine(  938):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  938): processMsg: DriverStartedState
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  938):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  938): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  938): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=147459
E/WifiStateMachine(  938): processMsg: DisconnectedState
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=99022
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=99022
E/WifiStateMachine(  938): Network connection established
D/WifiStateMachine(  938): fetchFrequency(), freq = 2412
E/WifiStateMachine(  938): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  938): NetworkAgent == null
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  938): handleMessage: new destination call exit/enter
D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
E/WifiStateMachine(  938): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  938): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  938): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  938): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  938): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  938): invokeEnterMethods: L2ConnectedState
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  938): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  938): NetworkAgent == null
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 20
,E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 21
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:1
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  938): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
E/WifiStateMachine(  938): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  938): Got NetworkAgent Messenger
E/WifiStateMachine(  938): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  938): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  938): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  938): NetworkAgent connected
W/WifiHW  (  938): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1411): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1411): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1411): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1411): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1411): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1411): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  938): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  938): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  938): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  938): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  938): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  938): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1411): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1411): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1411): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1411): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1411): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1411): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  938): Start Dhcp Watchdog 2
E/WifiStateMachine(  938): handleMessage: X
D/WISPrService( 5994): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  938): handleMessage: E msg.what=147462
E/WifiStateMachine(  938): processMsg: ObtainingIpState
E/WifiStateMachine(  938):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=99043  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=99044  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=99044  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  938): handleMessage: X
D/WISPrService( 5994): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  938): handleMessage: E msg.what=131155
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
E/WifiStateMachine(  938): processMsg: ObtainingIpState
D/libc    ( 5994): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5994): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  938):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2467] from screen [on:0 period:-1023123972] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1023123971] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  938):  get link layer stats 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WISPrService( 5994): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/FlexNetS( 6476): updateSvcAllowedInSettings:false
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:0
D/wpa_supplicant( 1411): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1411): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  938): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  938): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=108.00 txretriesrate=0.00 rxrate=142.00 userTriggerdPenalty0
E/WifiStateMachine(  938):  good link -> stuck count =0
E/WifiStateMachine(  938):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  938):  isHighRSSI       ---> score=65
E/WifiStateMachine(  938): calculateWifiScore() report new score 60
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:1
I/ActivityManager(  938): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6695 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
E/WifiStateMachine(  938): handleMessage: X
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  938): handleMessage: E msg.what=131212
D/ConnectivityService(  938): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  938): processMsg: ObtainingIpState
E/WifiStateMachine(  938):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
D/ConnectivityService(  938): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  938):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiStateMachine(  938): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  938): processMsg: DriverStartedState
D/PMS     (  938): acquireWL(12a55a4f): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 938 1000 null
E/WifiStateMachine(  938):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  938): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=196612
D/WifiStateMachine(  938): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  938): processMsg: ObtainingIpState
E/WifiStateMachine(  938):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=216,0,0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
,E/WifiStateMachine(  938):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=216,0,0
D/WifiDataStallTracker(  938): setDhcpActive: true
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WifiService(  938): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  938): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  938): do suspend false
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/FlexNetS( 6476): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:1
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1411): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1411): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1411): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiP2pService(  938): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15ccfc3d target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1411): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/WifiP2pService(  938): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15ccfc3d target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1411): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  938): Unexpected BatchedScanResults :null
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  938): noteBatchedScanstop()
E/WifiStateMachine(  938): handleMessage: X
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,W/ContextImpl(  938): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false,
,D/TetherSettings( 5994): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 5994): Cust_ConnectToPC   : Internet_Sharing>true
W/ContextImpl( 5994): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 5994): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5994): Cust_ConnectToPC   : spcsc>false
D/        ( 5994): Cust_ConnectToPC   : IPT>true
D/        ( 5994): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5994): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5994): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5994): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5994): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
,I/SmartNS_Utility( 5994): setISNotification
D/SmartNS_Utility( 5994): usb_cable_connect = 1
,D/SmartNS_Utility( 5994): usb_denied = 0,
,I/SmartNS_PSService( 5994): usb notificaiton:true
,E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5994): usb_cable_connect = 1
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL false Token 22 num clients 8
D/SmartNS_Utility( 5994): usb_denied = 0
I/SmartNS_PSService( 5994): usb notificaiton:true
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartNS_NSReceiver( 5994): Tethered state change:false isNSOpening:false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1224): reapply : com.android.settings 2 36
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,I/RemoteViews( 1224): reapply : com.android.settings 1 36
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6695): [b82.2.]  listen tmrbb8,
D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false,
D/MdProvGlob( 6666): remove item 101 (p2d26in181) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6695): [b82.2.] summary 118:p2 ignore
,D/MdProvGlob( 6666): remove item 101 (p2in8) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false
,D/FlexNetS( 6476): updateSvcAllowedInSettings:false,
,E/dhcpcd  ( 6722): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6722): version 5.5.6 starting
E/dhcpcd  ( 6722): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6722): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6722): autoip env[11]:autoip=DISABLE
,I/ActivityManager(  938): Killing 5812:com.google.android.talk/u0a112 (adj 15): empty #17
,D/Process (  938): killProcessQuiet, pid=5812
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6722): wlan0: rebinding lease of 192.168.1.130,
I/dhcpcd  ( 6722): wlan0: sending REQUEST (xid 0xbe371437), next in 1.70 seconds
,I/ActivityManager(  938): Recipient 5812
,E/WifiStateMachine(  938): handleMessage: E msg.what=131155
E/WifiStateMachine(  938): processMsg: ObtainingIpState,
,E/WifiStateMachine(  938):  ObtainingIpState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=108.0, 0.0, 0.0  rx=142.0 bcn=0 [on:0 tx:0 rx:0 period:505] from screen [on:0 period:-1023123438] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=108.0, 0.0, 0.0  rx=142.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1023123437] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938): handleMessage: X
,I/HtcModeClient( 3230): handler message = 4011,
E/HtcModeClient( 3230): Check connection and retry 12 times.
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL false Token 22 num clients 8,
,D/wpa_supplicant( 1411): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1411): EAPOL: disable timer tick
,D/Process (  938): killProcessQuiet, pid=5972
I/ActivityManager(  938): Killing 5972:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  938): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  938): handleMessage: E msg.what=131212
E/WifiStateMachine(  938): processMsg: ObtainingIpState
,E/WifiStateMachine(  938):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  938): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  938): handleMessage: X
D/ConnectivityService(  938): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/ActivityManager(  938): Recipient 5972,
,I/dhcpcd  ( 6722): wlan0: sending REQUEST (xid 0xbe371437), next in 2.66 seconds,
,I/dhcpcd  ( 6722): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6722): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6722): autoip env[11]:autoip=DISABLE
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  938): handleMessage: E msg.what=131212
,E/WifiStateMachine(  938): processMsg: ObtainingIpState
E/WifiStateMachine(  938):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
D/ConnectivityService(  938): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  938):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  938): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  938): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  938): handleMessage: X
,I/dhcpcd  ( 6722): bind_interface: daemonise
,D/libc    (  938): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  938): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  938): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  938): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  938): handleMessage: E msg.what=196613
E/WifiStateMachine(  938): processMsg: ObtainingIpState
E/WifiStateMachine(  938):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  938): processMsg: L2ConnectedState
,E/WifiStateMachine(  938):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  938): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1411): Power_Mode_Type mode = 0
I/wpa_supplicant( 1411): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  938): setDhcpActive: false
E/WifiStateMachine(  938): handlePostDhcpSetup release wake lock during DHCP
,D/PMS     (  938): releaseWL(12a55a4f): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  938): WifiStateMachine DHCP successful
E/WifiStateMachine(  938): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  938): link address 192.168.1.130/24
,E/WifiStateMachine(  938): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  938): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  938): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  938): gateway: /192.168.1.1
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1411): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1411): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  938): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=131210
E/WifiStateMachine(  938): processMsg: ObtainingIpState
E/WifiStateMachine(  938):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1411): environment dirty rate=40 [5][2][0]
,E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  938): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1411): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1411): wlan0: BLACKLIST CLEAR 
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiMonitor(  938): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=44 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  938): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  938): NetworkAgent != null
D/ConnectivityService(  938): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -63, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,E/WifiStateMachine(  938): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -63, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
V/NetworkPolicy(  938): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  938): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  938): WAN detection
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL true Token 22
D/HtcWifiWanDetect(  938): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiTrafficPoller(  938):  packet count Tx=218 Rx=287
D/ConnectivityService(  938): Adding iface wlan0 to network 101
E/WifiTrafficPoller(  938): notifying of data activity 3
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiDataStallTracker(  938): ENABLE_DATA_MONITOR_POLL true Token 2
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  938): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  938): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  938): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/ActivityManager(  938): Killing 6379:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  938): killProcessQuiet, pid=6379
,D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/WIFI_ICON( 1224): WifiActivity: 3
,D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/ConnectivityService(  938): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  938): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  428): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  938): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  428): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  938): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  428): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  938): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  428): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
,I/QuickSettingWifi( 1224): receive.wifiConnect:true wifiAPname:NG700 elapse:1,
,I/ActivityManager(  938): Recipient 6379
D/Process (  938): killProcessQuiet, pid=6356
I/ActivityManager(  938): Killing 6356:com.htc.cs.dm/u0a99 (adj 15): empty #18
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  938): Recipient 6356
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  938): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): Connected
D/ConnectivityService(  938): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  938): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): Validated
D/ConnectivityService(  938): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  938): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  938):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  938):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  938): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  938):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938): currentScore = 0, newScore = 20
D/ConnectivityService(  938):    accepting network in place of null
D/ConnectivityService(  938): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/CSLegacyTypeTracker(  938): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  938): sendGeneralBroadcast, restrictEnable=false
E/WifiStateMachine(  938): transitionTo: destState=ConnectedState
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  938): handleMessage: new destination call exit/enter
E/WifiStateMachine(  938): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  938): invokeExitMethods: ObtainingIpState
D/ConnectivityService(  938): sendGeneralBroadcastDelayed, restrictEnable=false
E/WifiStateMachine(  938): moveTempStackToStateStack: i=0,j=5
D/ConnectivityService(  938): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  938): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  938): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  938): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  938): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WISPrService( 5994): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  938): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
V/NetworkPolicy(  938): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  938): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  938): Validated
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  938): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  938): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  938):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL true Token 23
D/ConnectivityService(  938): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  938): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1224): CM callback handler got msg 524290
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiTrafficPoller(  938):  packet count Tx=219 Rx=287
D/ConnectivityService(  938): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiTrafficPoller(  938): notifying of data activity 2
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  938): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/SecurityController( 1224): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  938): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityManager.CallbackHandler( 1224): CM callback handler got msg 524290
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/usbnet  (  938): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  938): ensureActiveMobilePolicyLocked()
D/usbnet  (  938):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI_ICON( 1224): WifiActivity: 2
D/usbnet  (  938): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/PMS     (  938): acquireWL(f88cc61): PARTIAL_WAKE_LOCK  NetworkStats 0x1 938 1000 null
D/Tethering(  938): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  938): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
I/SecurityController( 1224): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiStateMachine(  938): updateDefaultRouteMacAddress reachable (tried again) :192.168.1.1 found c0:ff:d4:d3:aa:48
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/WifiStateMachine(  938): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/DATA_ICON( 1224): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
E/WifiStateMachine(  938): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/NetworkPolicy(  938): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
E/WifiStateMachine(  938): handleMessage: X
D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
D/WIFI    (  938): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  938): updateNetworkEnabledLocked()
,D/WIFI    (  938):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  938): updateIfacesLocked()
D/WIFI    (  938): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
V/NetworkPolicy(  938): updateNotificationsLocked()
D/WIFI    (  938): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  938):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  938): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiStateMachine(  938): handleMessage: E msg.what=131131
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  938): handleMessage: X
D/ConnectivityService(  938): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkManagementService(  938): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/ConnectivityService(  938):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  938):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  938): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  938): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/DATA_ICON( 1224): dataConnected: false/false
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/ConnectivityService(  938): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1224): CM callback handler got msg 524290
,D/DATA_ICON( 1224): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,I/SecurityController( 1224): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WISPrService( 5994): >>>>>WISPrService start isConnected = true<<<<<
D/PMS     (  938): releaseWL(f88cc61): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/DATA_ICON( 1224): dataConnected: false/false
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,V/NetworkPolicy(  938): updateNetworkEnabledLocked()
V/NetworkPolicy(  938): updateNotificationsLocked()
,I/QuickSettingWifi( 1224): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  938): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  938): acquireWL(3f8ac386): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 938 1000 null
D/GpsLocationProvider(  938): [handleMessage] UPDATE_NETWORK_STATE
I/AlarmManager(  938): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  938): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1495): [onReceive] WIFI(1): CONNECTED
,D/htcCheckinService(  938): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/ActivityManager(  938): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6759 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/GpsLocationProvider(  938): No APN found to select.
,D/PMS     (  938): releaseWL(3f8ac386): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  938): acquireWL(2430e474): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 938 1000 null
,D/PMS     (  938): releaseWL(2430e474): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MdScPhnSt( 6695): [7ea.1.]  listen tmrbb8,
,D/MdScDataSum( 6695): [7ea.1.] summary 118:p1 ignore
,E/WifiStateMachine(  938): handleMessage: E msg.what=131155,
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=108.0, 0.0, 0.0  rx=142.0 bcn=0 [on:0 tx:0 rx:0 period:2482] from screen [on:0 period:-1023120954] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=108.0, 0.0, 0.0  rx=142.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1023120953] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938):  get link layer stats 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1411): environment dirty rate=0 [2][0][0]
,E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiStateMachine(  938): BroadcastRSSIForIMS, newrssi =-63 , oldRssi= -200
E/WifiConfigStore(  938): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
E/WifiStateMachine(  938): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=55.50 txretriesrate=0.00 rxrate=73.00 userTriggerdPenalty0
E/WifiStateMachine(  938):  good link -> stuck count =0
E/WifiStateMachine(  938):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  938):  isHighRSSI       ---> score=65
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  938): handleMessage: X
,D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
,I/MusicStore( 6759): Database version: 120
,D/PMS     (  938): acquireWL(31b1d3e0): PARTIAL_WAKE_LOCK  *alarm* 0x1 938 1000 WorkSource{1000}
,V/AlarmManager(  938): sending alarm PendingIntent{b26a564: PendingIntentRecord{153113cd android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454970792420, Int=20000
,D/VoldConnector(  938): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6759): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  938): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6759): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  938): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6759): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/ResourcesManager( 6759): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6759): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6759): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6759): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6759): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35cee1a2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6759): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6759): GMSCore installation verified
,I/ConfigStore( 6759): Config Database version: 1,
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6759, uid=10159, userID:0,
,D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: ,
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
,D/MediaRouterService(  938): Client com.google.android.music (pid 6759): Registered
,D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
,I/MediaRouter( 6759): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6759): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6759): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6759): type=WIFI subType= reason=null isConnected=true
,D/AutoSetting( 1591): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6759, uid=10159, userID:0
,D/AutoSetting( 1591): service - onCreate()
,D/MobileConnectivityChangeReceiver( 6633): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6633): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1591): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1591): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1591): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1591): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1591): service - handleMessage() setting current location null
,D/LocationManagerService(  938): request 2ba52edf passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  938): provider request: passive ProviderRequest[ON interval=0]
,I/GHttpClientFactory( 6759): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/Kids    ( 4440): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8
,I/ActivityManager(  938): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6800 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GoogleURLConnFactory( 6759): Using platform SSLCertificateSocketFactory
,D/Process (  938): killProcessQuiet, pid=6061
,I/ActivityManager(  938): Killing 6061:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 6800): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  938): Recipient 6061
,D/PMS     (  938): releaseWL(1a0d9580): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  938): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8,
D/WIFI_ICON( 1224): WifiActivity: 1
E/WifiTrafficPoller(  938):  packet count Tx=219 Rx=288
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  938): notifying of data activity 1
,I/Babel_SMS( 6800): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6800): MmsConfig.loadMmsSettings
,I/ActivityManager(  938): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6828 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6800, uid=10112, userID:0
,W/HtcWrapAdjustableCursorFactory( 6828): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 6828): onCreate
,D/MmsCustomizationProvider( 6828): query uri: content://htc-mms-customization/mms-ua/ua_string,
V/GetPrviateResource( 6828): GetPrviateResource
,W/Settings( 6800): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/GetPrviateResource( 6828): GetPrviateResource
,I/Babel_Crash( 6800): startup - clean
,D/MmsCustomizationProvider( 6828): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 6800): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6800): MmsConfig.loadFromDatabase
,D/MessageCustFlag( 6828): sense_version=6.0
,D/BTAccessoryUtil( 6828): createReceiver
,D/BTAccessoryUtil( 6828): registerReceiver return intent = null
,D/MessageCustFlag( 6828): sku_id=118
,D/HtcBuildUtils( 6828): getRATByHtcTelephonyCapability:1
,W/SystemReader( 6828): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6800): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6800): MmsConfig.loadFromResources
,I/Babel   ( 6800): deleted: false for 0
E/Babel_SMS( 6800): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6800): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6800, uid=10112, userID:0
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6800, uid=10112, userID:0
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6800, uid=10112, userID:0
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6800, uid=10112, userID:0
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6800, uid=10112, userID:0
,I/ActivityManager(  938): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6856 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/VideoCapabilities( 6800): Unrecognized profile 2130706433 for video/avc
,I/art     (  456): Explicit concurrent mark sweep GC freed 8639(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 184us total 20.871ms
,W/VideoCapabilities( 6800): Unsupported mime video/x-ms-wmv
I/art     (  456): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 138us total 15.621ms
,W/Utils   ( 6800): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 6800): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6800): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6800): Unsupported mime audio/qcelp,
,W/VideoCapabilities( 6800): Unsupported mime video/x-ms-wmv
,I/art     (  456): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 132us total 15.905ms
,I/VideoCapabilities( 6800): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6800): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6800): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6800): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6800): Unrecognized profile 2130706433 for video/avc,
,D/Process (  938): killProcessQuiet, pid=6406
I/ActivityManager(  938): Killing 6406:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  938): Recipient 6406,
,E/WifiDataStallTracker(  938): DATA_MONITOR_POLL true Token 3,
,I/vclib   ( 6800): onServiceConnected,
W/Babel   ( 6800): Attempted to change video mute state without an active call.
,D/VoldConnector(  938): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6856): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  938): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,D/libc    ( 6800): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6800): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6800): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6800): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6800): [NET] android_getaddrinfo_proxy+
D/libc    ( 6800): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  428): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024,
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
D/libc    (  428): [NET] _dns_getaddrinfo+, netid:101, mark:917605
W/ContextImpl( 6856): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6856): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6856):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6856):   adb logcat -s GAv4
,D/VoldConnector(  938): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6856): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/VoldConnector(  938): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,W/GAv4    ( 6856): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6856): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6856): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6856): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,D/libc    (  428): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6800): [NET] android_getaddrinfo_proxy-, success
,I/Babel   ( 6800): connection state changed from UNKNOWN to CONNECTED
,D/Process (  938): killProcessQuiet, pid=5586
I/ActivityManager(  938): Killing 5586:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  938): Recipient 5586,
,W/global  ( 6856): [apache-http] Connection GC has been deprecated!
,W/global  ( 6856): [apache-http] Connection GC has been deprecated!
,E/WifiStateMachine(  938): handleMessage: E msg.what=131168
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  938): handleMessage: X
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  938):  packet count Tx=224 Rx=292
D/WIFI_ICON( 1224): WifiActivity: 3
E/WifiTrafficPoller(  938): notifying of data activity 3,
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/WebViewFactory( 6856): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6856): Time to load native libraries: 1 ms (timestamps 3914-3915),
I/LibraryLoader( 6856): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6856): Binding Chromium to main looper Looper (main, tid 1) {3d407a53},
,I/LibraryLoader( 6856): Expected native library version number "",actual native library version number "",
,I/chromium( 6856): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6856): Initializing chromium process, singleProcess=true,
W/art     ( 6856): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6856): ApplicationContext is null in ApplicationStatus
,W/chromium( 6856): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6856): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6856): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6856): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6856): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6856): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6856): Local Branch: 
I/Adreno-EGL( 6856): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6856): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6856):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6856): Requires BLUETOOTH permission,
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6554): 
,I/art     (  938): Explicit concurrent mark sweep GC freed 57139(2MB) AllocSpace objects, 5(164KB) LOS objects, 33% free, 16MB/25MB, paused 1.565ms total 141.400ms,
,I/NSApplication( 6856): Starting up...
,I/ActivityManager(  938): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6919 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  938): killProcessQuiet, pid=6092
I/ActivityManager(  938): Killing 6092:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  938): Recipient 6092
,D/libc    (  938): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  938): [NET] android_getaddrinfofornet-, err=8
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  938): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  938): [NET] android_getaddrinfo_proxy+
D/libc    (  938): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  428): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  428): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  428): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
D/HtcWifiWanDetect(  938): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  938): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  938): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6943 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  938): Killing 5935:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  938): killProcessQuiet, pid=5935
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  938): Recipient 5935
,I/HtcModeClient( 3230): handler message = 4011,
,E/HtcModeClient( 3230): Check connection and retry 12 times. Stop service and kill this process.,
,D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/HtcModeClient( 3230): Don't start project servcice
,D/HtcModeClient( 3230): setEject: MEDIA_EJECT_STATE = true
I/AlarmManager(  938): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  938): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  938): acquireWL(33db5e18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 938 1000 null
,D/GpsLocationProvider(  938): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  938): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1495): [onReceive] WIFI(1): CONNECTED
D/HtcModeClient( 3230): connectState: CONNECTION_READY = false
D/SilentMusic( 3230): call stop
D/HtcModeClient( 3230): close connection
W/HtcModeClient( 3230): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3230): read the terminate packet, so break
,I/NetworkMonitor( 6759): type=WIFI subType= reason=null isConnected=true
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  938):  packet count Tx=225 Rx=294
,D/htcCheckinService(  938): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,W/ResourcesManager( 6943): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/GpsLocationProvider(  938): No APN found to select.
,D/PMS     (  938): releaseWL(33db5e18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  938): acquireWL(aa01e56): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 938 1000 null
,D/PMS     (  938): releaseWL(aa01e56): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/MdScPhnSt( 6695): [a8.1.]  listen tmrbb8
,D/MdScDataSum( 6695): [a8.1.] summary 118:p1 ignore
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6554): 
,D/Process (  938): killProcessQuiet, pid=3230,
I/ActivityManager(  938): Killing 3230:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/Messaging( 6828): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6828): networkCode: 
,D/MessageCustFlag( 6828): sku_id=118,
D/MmsConfig( 6828): SIE smsPri: null
D/MmsConfig( 6828): networkCode: ,
,D/MmsConfig( 6828): packageName: com.htc.vvm.att does not exist,
D/Messaging( 6828): mNeedToUpdateDate2 start,
D/ReportIndicatorCache( 6828): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 6828): 
D/MmsAsyncWorkHandler( 6828): HM tk = 20001
D/ReportIndicatorCache( 6828): MSG_QUERY_REPORTS >>,
,D/SettingsManager( 6828): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@f820bfc
,I/ActivityManager(  938): Recipient 3230
D/DraftCache( 6828): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6828): [DraftCache/1] refresh
,D/MmsConfig( 6828): networkCode: 
,D/Messaging( 6828): ViewCache CreatePreloadOnlyConversationList
I/Messaging( 6828): mccmnc> 
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6554): 
,D/MessageCustFlag( 6828): sense_version=6.0,
,D/Jerry   ( 6828): start to preload cursor >>>>>>>
,E/WifiStateMachine(  938): handleMessage: E msg.what=131155
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=55.5, 0.0, 0.0  rx=73.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1023117946] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=55.5, 0.0, 0.0  rx=73.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1023117945] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938):  get link layer stats 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1411): environment dirty rate=14 [7][1][0]
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
,E/WifiConfigStore(  938): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
,D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  938): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=31.25 txretriesrate=0.00 rxrate=39.50 userTriggerdPenalty0
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  938):  good link -> stuck count =0
E/WifiStateMachine(  938):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  938):  isHighRSSI       ---> score=65
D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1438):  slotId = -1000
D/MmsSmsV2Provider( 1438): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
,E/WifiStateMachine(  938): handleMessage: X
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
,D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PhoneStorageUtil( 6828): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6828): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6828): createReceiver
,D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/AccFlag ( 1438): sku_id=118
,D/DraftCache( 6828): [DraftCache/166] rebuildCache
,D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/MmsSmsV2Provider( 1438):  slotId = -1000
D/MmsSmsV2Provider( 1438): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1438): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
V/MmsProvider( 1438): Update uri=content://mms, match=0
V/MmsProvider( 1438): selection=st=129 AND m_type!=134
,D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83,
D/MmsSmsV2Provider( 1438):  slotId = -1000
D/Messaging( 6828): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6828): TransactionService is going to be woken up.
,V/TransactionService( 6828): 1-Creating TransactionService
D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1438):  slotId = -1000
D/MmsSmsV2Provider( 1438): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 6828): ViewCache CreatePreload
D/Messaging( 6828): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 6828): onStartCommand: 1
D/MmsSystemEventReceiver( 6828): unRegisterForConnectionStateChanges
,D/Messaging( 6828): mNeedToUpdateDate2: false,
V/TransactionService( 6828): 4-Handling incoming message: { when=-2ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6828): Loading previous transactions.
,D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
D/Jerry   ( 1438): URI_DRAFT
,D/DraftCache( 6828): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 6828): [DraftCache/166] rebuildCache time: 2
D/MmsAsyncWorkHandler( 6828): 
D/MmsAsyncWorkHandler( 6828): HM tk = 20002
,D/Cust_MMSMS( 6828): _has_set_default_values_2=true
,D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1438):  slotId = -1000
D/MmsSmsV2Provider( 1438): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 6828): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1438): device_type: 1
,D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97,
D/AccFlag ( 1438): sku_id=118
D/MsgPreferenceUtils( 6828): def_index: 0
,D/MsgPreferenceUtils( 6828): globalIndex = 1
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6554): 
D/TransactionService( 6828): Force clearing mTransactionList
D/TransactionService( 6828): Force set service start id to 1
V/TransactionService( 6828): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 6828): unRegisterForConnectionStateChanges
,V/TransactionService( 6828): Destroying TransactionService
D/TransactionService( 6828): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 6828): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1438): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1438): sku_id=118
,D/MsgPreferenceUtils( 6828): phone state: true
D/MsgPreferenceUtils( 6828): sd state: false
D/MsgPreferenceUtils( 6828): vIndex = 0
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6554): 
,D/Process (  938): killProcessQuiet, pid=6449
I/ActivityManager(  938): Killing 6449:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/art     ( 6943): Suspending all threads took: 7.698ms
,I/ActivityManager(  938): Recipient 6449
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6554): 
,W/SystemReader(  938): Cannot find grip_rejection_width, use default value instead,
,D/AccTypeManager( 1714): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/ResourcesManager(  938): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1495): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Launcher( 1495): Deferring update until onResume
,D/Launcher( 1495): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1714): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PhoneApp( 1438): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AccTypeManager( 1714): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,E/ExternalAccountType( 1714): Unsupported attribute readOnly
,W/PackageManager(  938): Unable to load service info ResolveInfo{367b2a97 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  938): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  938): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  938): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  938): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  938): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  938): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  938): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  938): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  938): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  938): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  938): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1840): DISABLE
,I/GCoreNlp( 1840): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,I/BackupManagerService(  938): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
E/WifiStateMachine(  938): WiFiStateMachine SCAN ALARM
D/PMS     (  938): releaseWL(31b1d3e0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  938): handleMessage: E msg.what=131143
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:79 rssi=-63 f=2412 sc=60 link=72 tx=31.2, 0.0, 0.0  rx=39.5 list=2412 [on:0 tx:0 rx:0 period:487] from screen [on:0 period:-1023117447]
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:79 rssi=-63 f=2412 sc=60 link=72 tx=31.2, 0.0, 0.0  rx=39.5 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1023117446]
E/WifiStateMachine(  938): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=31.25 rxSuccessRate=39.50 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-63
E/WifiStateMachine(  938): WifiStateMachine CMD_START_SCAN with age=69029 interval=40000 maxinterval=300000
E/WifiStateMachine(  938): WifiStateMachine CMD_START_SCAN try full band scan age=69029 interval=40000 maxinterval=300000
E/WifiStateMachine(  938): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  938): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  938): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  938): has c0:ff:d4:d3:aa:48 freq=2412 age=490 ?=true
E/WifiStateMachine(  938): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1411): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1411): wpa_supplicant_scan enter
D/wpa_supplicant( 1411): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1411): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1411): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1411): WPS:  * Request Type
D/wpa_supplicant( 1411): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1411): WPS:  * UUID-E
D/wpa_supplicant( 1411): WPS:  * Primary Device Type
D/wpa_supplicant( 1411): WPS:  * RF Bands (3)
D/wpa_supplicant( 1411): WPS:  * Association State
D/wpa_supplicant( 1411): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1411): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1411): WPS:  * Manufacturer
D/wpa_supplicant( 1411): WPS:  * Model Name
D/wpa_supplicant( 1411): WPS:  * Model Number
D/wpa_supplicant( 1411): WPS:  * Device Name
D/wpa_supplicant( 1411): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1411): P2P: * P2P IE header
D/wpa_supplicant( 1411): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1411): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1411): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1411): wlan0: Add radio work 'scan'@0x556afd4860
,D/wpa_supplicant( 1411): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1411): wlan0: Starting radio work 'scan'@0x556afd4860 after 0.000030 second wait
D/wpa_supplicant( 1411): wlan0: nl80211: scan request
E/WifiStateMachine(  938): [1,454,970,795,899 ms] noteScanstart no scan source
D/wpa_supplicant( 1411): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1411): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1411): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1411): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1411): wlan0: Own scan request started a scan in 0.000071 seconds
I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  938): handleMessage: X
D/WifiMonitor(  938): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  938): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  938): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/MusicLeanback( 6759): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/LocationProviderProxy(  938): applying state to connected service
D/PMS     (  938): acquireWL(2a24043f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  938): releaseWL(2a24043f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/AutoSetting( 1591): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6633): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/LocationProviderProxy(  938): applying state to connected service
,D/MobileConnectivityChangeReceiver( 6633): onReceive CONNECTIVITY_CHANGE networkType=1
,D/PMS     (  938): acquireWL(2c5ea55b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(2c5ea55b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  938): acquireWL(3a1051f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
D/AutoSetting( 1591): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1591): Util - check NLP state, Allowned:false, Enabled:false
D/PMS     (  938): releaseWL(3a1051f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AutoSetting( 1591): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1591): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1591): service - handleMessage() setting current location null
,D/PMS     (  938): acquireWL(bb76810): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(bb76810): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4440, uid=10024, userID:0
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/Kids    ( 4440): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
D/wpa_supplicant( 1411): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1411): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1411): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1411): wlan0: Event SCAN_RESULTS (3) received
,I/wpa_supplicant( 1411): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1411): wlan0: Scan completed in 0.072388 seconds
D/wpa_supplicant( 1411): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1411): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1411): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1411): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1411): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1411): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1411): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
D/wpa_supplicant( 1411): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1411): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1411): wlan0: Scan-only results received
D/wpa_supplicant( 1411): wlan0: Radio work 'scan'@0x556afd4860 done in 0.073041 seconds
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  938): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  938): handleMessage: E msg.what=147461
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  938): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1411): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  938): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  938): [1,454,970,795,976 ms] noteScanEnd no scan source
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1411): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  938): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@1130d168 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  938): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  938): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  938): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  938): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  938):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-63 freq=2412
E/WifiAutoJoinController (  938): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  938): ageScanResultsOut delay 40000 size 3 now 1454970795979
E/WifiAutoJoinController (  938): newSupplicantResults size=3 known=1 true
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1411): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  938): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  938): ssid=,NG700
E/WifiAutoJoinController (  938): id=0
E/WifiAutoJoinController (  938): mode=station
E/WifiAutoJoinController (  938): pairwise_cipher=CCMP
E/WifiAutoJoinController (  938): group_cipher=CCMP
E/WifiAutoJoinController (  938): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  938): wpa_state=COMPLETED
E/WifiAutoJoinController (  938): ip_address=192.168.1.130
E/WifiAutoJoinController (  938): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  938): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  938): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  938): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  938): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController (  938): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  938): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-63 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  938): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  938): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  938): Done attemptAutoJoin status=0
E/WifiConfigStore(  938):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  938): handleMessage: X
,D/PMS     (  938): acquireWL(2fec7b2f): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6800 10112 null
,I/ActivityManager(  938): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7009 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/PMS     (  938): releaseWL(2fec7b2f): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6800): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6800): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6800): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6800): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6800): Installed default security provider GmsCore_OpenSSL
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  938):  packet count Tx=229 Rx=295
,D/LocationManagerService(  938): getProviders()=[passive],
,I/ActivityManager(  938): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7038 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,I/[PluginManager]RegisterService( 1591): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1591): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4440): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4440): Null package name or gms related package.  Ignoreing.
,D/PMS     (  938): acquireWL(c4267ca): PARTIAL_WAKE_LOCK  Icing 0x1 4440 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): acquireWL(421ed3b): PARTIAL_WAKE_LOCK  AsyncService 0x1 6943 10167 null
,D/PMS     (  938): acquireWL(3d1e1b1): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6943 10167 null
I/Icing   ( 4440): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 7009): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  938): releaseWL(421ed3b): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,D/PMS     (  938): releaseWL(c4267ca): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(3d1e1b1): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,I/UpdateIcingCorporaServi( 7009): UpdateCorporaTask done [took 130 ms] updated apps [took 128 ms] 
,I/ActivityManager(  938): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=7072 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  938): acquireWL(1ab82217): PARTIAL_WAKE_LOCK  *alarm* 0x1 938 1000 WorkSource{10076}
V/AlarmManager(  938): sending alarm PendingIntent{2f93b604: PendingIntentRecord{e71e7ed com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454970796611, Int=60000
D/PMS     (  938): releaseWL(1ab82217): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 7072): SMSBackupAgentService started,
D/SMSBackup( 7072): Checking restore status
,D/SMSBackup( 7072): Restore complete,
D/SMSBackup( 7072): cancelCheckAlarm
,D/SMSBackup( 7072): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  938): killProcessQuiet, pid=5426
I/ActivityManager(  938): Killing 5426:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  938): Recipient 5426
,E/WifiDataStallTracker(  938): DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  938): updateDataStallInfo: mDataStallTxRxSum={txSum=202 rxSum=181} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  938): updateDataStallInfo: IN/OUT,
D/WifiDataStallTracker(  938): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1224): WifiActivity: 0
E/WifiTrafficPoller(  938):  packet count Tx=229 Rx=295
E/WifiTrafficPoller(  938): notifying of data activity 0
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1495): loadItems() com.htc.launcher.pageview.WidgetManager@43f6bff +
I/Prism.WidgetManager( 1495): onLoadItems() +
,W/ResourcesManager( 1495): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 1495): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1495): Copying FileAsset 0x559abd58c0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1495): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1495): onLoadItems() -
I/Prism.ItemManager( 1495): loadItems() com.htc.launcher.pageview.WidgetManager@43f6bff -
,D/PMS     (  938): acquireWL(2982e70): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6759 10159 null,
,D/WearableService( 5730): callingUid 10024, callindPid: 5730,
,D/PhoneApp( 1438): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1438): -- N1 =0,
D/PhoneApp( 1438): -- N2 =0
D/PhoneApp( 1438): -- N3 =0
,E/GmsUtils( 6759): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6759): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     (  938): Explicit concurrent mark sweep GC freed 25663(1420KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 1.600ms total 145.030ms
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6759, uid=10159, userID:0
,D/PMS     (  938): releaseWL(2982e70): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6759): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6759): Stop autocaching.
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  938):  packet count Tx=229 Rx=295
,E/WifiStateMachine(  938): handleMessage: E msg.what=131155,
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=31.2, 0.0, 0.0  rx=39.5 bcn=0 [on:0 tx:0 rx:0 period:2514] from screen [on:0 period:-1023114931] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=31.2, 0.0, 0.0  rx=39.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1023114930] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938):  get link layer stats 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1411): environment dirty rate=0 [3][0][0]
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiConfigStore(  938): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
E/WifiStateMachine(  938): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=17.12 txretriesrate=0.00 rxrate=20.25 userTriggerdPenalty0
E/WifiStateMachine(  938):  good link -> stuck count =0
E/WifiStateMachine(  938):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  938):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -63, 3
E/WifiStateMachine(  938): handleMessage: X
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  938):  packet count Tx=229 Rx=295
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1224): WifiActivity: 2
E/WifiTrafficPoller(  938):  packet count Tx=230 Rx=295
E/WifiTrafficPoller(  938): notifying of data activity 2
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/Process (  938): killProcessQuiet, pid=6529,
I/ActivityManager(  938): Killing 6529:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  938): Recipient 6529
,D/Process (  938): killProcessQuiet, pid=6666,
I/ActivityManager(  938): Killing 6666:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL true Token 24 num clients 8
,D/WIFI_ICON( 1224): WifiActivity: 1
E/WifiTrafficPoller(  938):  packet count Tx=230 Rx=296
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  938): notifying of data activity 1
,I/ActivityManager(  938): Recipient 6666
,E/WifiStateMachine(  938): handleMessage: E msg.what=131155,
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=17.1, 0.0, 0.0  rx=20.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1023111907] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=17.1, 0.0, 0.0  rx=20.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1023111905] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938):  get link layer stats 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1411): environment dirty rate=0 [2][0][0]
,E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  938): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  938): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.06 txretriesrate=0.00 rxrate=10.62 userTriggerdPenalty0
E/WifiStateMachine(  938):  good link -> stuck count =0
E/WifiStateMachine(  938):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  938):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  938): RSSI current: 3 new: -62, 3
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  938): handleMessage: X
,I/jxcore-log( 6554): Test app app.js loaded,
I/jxcore-log( 6554): 
,I/chromium( 6554): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): 	Bluetooth MAC address: 90:E7:C4:F6:69:77, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): 	Advertise TX power level: 1, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6554): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25245edd added. We now have 1 listener(s)
D/BluetoothAdapter( 6554): 836889576: getState(). Returning 12,
I/jxcore-log( 6554): BLE advertisement is supported
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): TAP version 13,
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): ok 1 should be equal,
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # setup,
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 6554): 
,I/PMS     (  938): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  938): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@21dd52d2
W/SensorService(  938): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  938): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  938): pid=938, uid=1000
W/SensorService(  938): Active sensors: size = 4
W/PMN     (  938): goingToSleep
W/SensorService(  938): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  938): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  938): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  938): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  938): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@21dd52d2, eanble = 0, strlen(mName) = 91
W/SensorService(  938): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  938): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@20e2a811
W/SensorService(  938): Listener[1] = com.htc.smartdim.sensor_eye@213f8b85
W/SensorService(  938): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/PMS     (  938): mWirelessDisplayManager is null,
W/PMS     (  938): mWirelessDisplayManager is still null
D/PMS     (  938): acquireWL(35df44a3): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 938 1000 null
,W/PMN     (  938): goingToSleep done
,D/PMS     (  938): releaseWL(35df44a3): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/jxcore-log( 6554): ok 2 should be equal
I/jxcore-log( 6554): 
I/PMS     (  938): Sleeping (uid 1000)...
E/WifiDataStallTracker(  938): DATA_MONITOR_POLL true Token 3
D/XAN-DPS (  938): prepareColorFade 1
I/jxcore-log( 6554): ok 3 should be equal
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): ok 4 should be equal
I/jxcore-log( 6554): 
,W/HtcSystemUPManager(  938): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/jxcore-log( 6554): ok 5 should be equal
I/jxcore-log( 6554): 
D/AlarmManager(  938): ACTION_SCREEN_ON
I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
D/WifiDataStallTracker(  938): updateDataStallInfo: mDataStallTxRxSum={txSum=203 rxSum=182} preTxRxSum={txSum=202 rxSum=181}
D/WifiDataStallTracker(  938): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  938): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 6554): 
,E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL true Token 24
I/AlarmManager(  938): [AlarmQueuing] recover blocked alarms
E/WifiTrafficPoller(  938):  packet count Tx=231 Rx=297
I/AlarmManager(  938): [AlarmQueuing] done recovering
E/WifiTrafficPoller(  938): notifying of data activity 3
I/AlarmManager(  938): [AlarmQueuing] recover EPS screen off blocked alarms
E/WifiDataStallTracker(  938): ENABLE_DATA_MONITOR_POLL true Token 3
I/AlarmManager(  938): [AlarmQueuing] done EPS screen off alarm recovering
,W/HtcLockScreen( 1224): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
D/WifiDataStallTracker(  938): updateDataStallInfo: mDataStallTxRxSum={txSum=203 rxSum=182} preTxRxSum={txSum=203 rxSum=182}
D/WifiDataStallTracker(  938): updateDataStallInfo: NONE
D/WifiDataStallTracker(  938): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/jxcore-log( 6554): ok 6 should throw
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 6554): 
,E/WifiStateMachine(  938): handleMessage: E msg.what=131167
E/WifiStateMachine(  938): processMsg: ConnectedState
,E/WifiStateMachine(  938):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
I/Adreno-EGL(  938): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  938): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  938): Build Date: 03/09/15 Mon
I/Adreno-EGL(  938): Local Branch: 
I/Adreno-EGL(  938): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  938): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  938):                  d74aa161a12b9c6fc6332151
,E/WifiStateMachine(  938):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1411): SET_SCREEN_ON:On
I/wpa_supplicant( 1411): htc_wext_set_keepalive +
I/wpa_supplicant( 1411): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1411): getPrivFuncNum +	
I/wpa_supplicant( 1411): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1411): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1411): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1411): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1411): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  938): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  938): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  938): handleScreenStateChanged Exit: true
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=131154
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState,
E/WifiStateMachine(  938):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SIGNAL_POLL'
I/jxcore-log( 6554): ok 7 should throw
I/jxcore-log( 6554): 
I/wpa_supplicant( 1411): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  938): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  938): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  938): handleMessage: X
E/WifiStateMachine(  938): handleMessage: E msg.what=131127
E/WifiStateMachine(  938): processMsg: ConnectedState
,E/WifiStateMachine(  938):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
E/WifiStateMachine(  938):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  938): handleMessage: X
D/WIFI_ICON( 1224): WifiActivity: 3
E/WifiStateMachine(  938): handleMessage: E msg.what=131129
E/WifiStateMachine(  938): processMsg: ConnectedState
I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
,D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/jxcore-log( 6554): # #parseBeacons no beacons returns null
I/jxcore-log( 6554): 
E/WifiStateMachine(  938):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
V/SRS_Proc(  448): ParamSet string: screen_state=on
E/WifiStateMachine(  938):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/audio_a2dp_hw(  448): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  938):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1411): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1411): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  938): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiStateMachine(  938): handleMessage: X
E/WifiMonitor(  938): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST CLEAR 
D/NetworkPolicy(  938): updateScreenOn: false
V/NetworkPolicy(  938): updateIfacesLocked()
D/NetworkManagementService(  938): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WifiController(  938): handleMessage: E msg.what=155650
D/WifiController(  938): processMsg: DeviceActiveState
D/WifiController(  938): processMsg: StaEnabledState
D/WifiController(  938): processMsg: DefaultState
D/WifiController(  938): handleMessage: X
,D/GpsLocationProvider(  938): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/jxcore-log( 6554): ok 8 should be equal
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble,
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): ok 9 should throw
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
I/jxcore-log( 6554): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 6554): 
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1224): receive(android.intent.action.SCREEN_ON,1,false)
,D/PMS     (  938): acquireWL(131787ff): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1840 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  938): acquireWL(3aaec9cc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(131787ff): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(3aaec9cc): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/XAN-DPS (  938): prepareColorFade done
,I/ActivityManager(  938): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7112 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/XAN-DPS (  938): setBrightness to 0
,I/SensorManager(  938): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@20e2a811
,W/SensorService(  938): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  938): disable: get sensor name = CM32181 Light sensor
I/jxcore-log( 6554): ok 10 should be equal
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
I/DisplayManagerService(  938): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
W/SensorService(  938): pid=938, uid=1000
W/SensorService(  938): Active sensors: size = 3
W/SensorService(  938): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  938): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  938): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  938): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@20e2a811, eanble = 0, strlen(mName) = 67
W/SensorService(  938): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  938): Listener[0] = com.htc.smartdim.sensor_eye@213f8b85
W/SensorService(  938): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/jxcore-log( 6554): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 6554): 
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
,V/ActivityManager(  938): Display changed displayId=0
D/AlarmManager(  938): ACTION_SCREEN_OFF
,E/WifiTrafficPoller(  938): ENABLE_TRAFFIC_STATS_POLL false Token 25
I/AlarmManager(  938): [AlarmQueuing] screen off now: ,
,D/WifiDataStallTracker(  938): stopDataStallAlarm ,
,I/AlarmManager(  938): [AlarmQueuing] data connection: true
E/WifiDataStallTracker(  938): ENABLE_DATA_MONITOR_POLL false Token 4
I/AlarmManager(  938): [AlarmQueuing] wifi connection: true
E/WifiStateMachine(  938): handleMessage: E msg.what=131167
D/WifiDisplayAdapter(  938): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  938):     Client/Owner: Client
D/WifiDisplayAdapter(  938):     GroupId: 
D/WifiDisplayAdapter(  938):     Passphrase: 
D/WifiDisplayAdapter(  938):     SessionId: 0
D/WifiDisplayAdapter(  938):     IP Address: }
E/WifiStateMachine(  938): processMsg: ConnectedState
D/NetworkPolicy(  938): updateScreenOn: false
E/WifiStateMachine(  938):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
,V/NetworkPolicy(  938): updateIfacesLocked()
E/WifiStateMachine(  938): processMsg: L2ConnectedState
D/NetworkManagementService(  938): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  938):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  938): processMsg: DefaultState
V/SRS_Proc(  448): ParamSet string: screen_state=off
E/audio_a2dp_hw(  448): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  938):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  938):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  938): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1411): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1411): SET_SCREEN_ON:Off
I/wpa_supplicant( 1411): htc_wext_set_keepalive +
I/wpa_supplicant( 1411): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1411): getPrivFuncNum +	
I/wpa_supplicant( 1411): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1411): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1411): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1411): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1411): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  938): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
,D/WifiStateMachine(  938): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  938): handleScreenStateChanged Exit: false
E/WifiStateMachine(  938): handleMessage: X
D/WifiController(  938): handleMessage: E msg.what=155651
E/WifiStateMachine(  938): handleMessage: E msg.what=131154
D/WifiController(  938): processMsg: DeviceActiveState
E/WifiStateMachine(  938): processMsg: ConnectedState
D/WifiController(  938): processMsg: StaEnabledState
D/WifiController(  938): processMsg: DefaultState
D/WifiController(  938): handleMessage: X
E/WifiStateMachine(  938):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  938): handleMessage: X
D/GpsLocationProvider(  938): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
I/SensorManager( 1224): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@1d00e30d, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,I/jxcore-log( 6554): ok 11 (unnamed assert)
I/jxcore-log( 6554): 
,W/SensorService(  938): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  938): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  938): pid=1224, uid=10041
W/SensorService(  938): Active sensors: size = 4
W/SensorService(  938): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  938): CM36686 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  938): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  938): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  938): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@1d00e30d, eanble = 1, strlen(mName) = 57
W/SensorService(  938): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  938): Listener[0] = com.htc.smartdim.sensor_eye@213f8b85
W/SensorService(  938): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@1d00e30d
W/SensorService(  938): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/jxcore-log( 6554): ok 12 should be equal
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 6554): 
D/DotMatrix( 1311): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1438): start background delete task...
,I/IntentController( 1224): receive(android.intent.action.SCREEN_OFF,1,false)
,W/ContextImpl( 7112): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/ContactMessageStore( 1438): size: 0 , 0
D/ContactMessageStore( 1438): Background delete complete
,D/PMS     (  938): acquireWL(14e4b6b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(14e4b6b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  938): acquireWL(1f5e0c91): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 7112): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  938): releaseWL(1f5e0c91): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL false Token 26 num clients 8
,D/PowerUsageList:PowerUsageHelper( 7112): MY_DEBUG = false
,D/SmartSyncUtils( 7112): isEpsOn(), nState = 0
,D/PMS     (  938): acquireWL(1ac077f7): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7112 1000 null,
,D/AutoSetting( 1591): service - mHandler: cancel location update
,D/AutoSetting( 1591): service -           changes count: 0
,D/PMS     (  938): releaseWL(1ac077f7): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/RemoteViews( 1224): setHTCTheme(com.htc.updater,true,33751145)
,W/ContextImpl(  938): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/SmartDim(  938): Init customizeScreenOffDelayClass error
,I/RemoteViews( 1224): apply : com.htc.updater 1 12 0 36
,I/jxcore-log( 6554): ok 13 (unnamed assert)
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): ok 14 (unnamed assert)
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # setup
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 6554): 
,W/ContextImpl( 7112): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 7112): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 7112): isEpsOn(), nState = 0
D/SmartSyncUtils( 7112): isEpsOn(), nState = 0
,W/ContextImpl( 7112): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  938): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  938): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@213f8b85,
W/SensorService(  938): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  938): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  938): pid=938, uid=1000,
W/SensorService(  938): Active sensors: size = 3
W/SensorService(  938): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  938): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  938): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  938): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@213f8b85, eanble = 0, strlen(mName) = 36
W/SensorService(  938): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  938): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1d00e30d
W/SensorService(  938): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  938): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  938): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  938): pid=938, uid=1000
W/SensorService(  938): Active sensors: size = 2
,W/SensorService(  938): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  938): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  938): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@213f8b85, eanble = 0, strlen(mName) = 36
W/SensorService(  938): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  938): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1d00e30d
W/SensorService(  938): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  938): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@213f8b85
E/ActivityThread(  938): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@326f1dda that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  938): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@326f1dda that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  938): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  938): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  938): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  938): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  938): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  938): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  938): 	,at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  938): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  938): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  938): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  938): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  938): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  938): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  938): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  938): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  938): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  938): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  938): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  938): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=7144 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/PowerUsageList:PowerUsageHelper( 7112): PowerProfile::POWER_SCREEN_FULL = 154.8,
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  938): Setting HAL interactive mode to false
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  938): Setting HAL interactive mode to false done
D/SurfaceControl(  938): Excessive delay in setPowerMode(): 315ms
D/PMS     (  938): Setting HAL auto-suspend mode to true
W/HtcSystemUPManager(  938): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  938): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  938): screenObserver, isScreenOn=false
D/StatusBarManagerService(  938): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  938): Disable input method client, pid=6554
,I/InputMethodManager( 6554): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{2b42bd71 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2151ea52
,I/jxcore-log( 6554): ok 15 (unnamed assert)
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): # teardown
I/jxcore-log( 6554): 
,I/InputManager(  938): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/PhoneStatusBar( 1224): setImeWindowStatus(false,false)
,D/HABCtrl (  938): TPE algorithm. remove timeout.
D/PMS     (  938): OOBE c monitor 11
D/PMS     (  938): acquireWL(3ccd5d82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 938 1000 null
I/BatteryService(  938): n_update end
D/PMS     (  938): releaseWL(3ccd5d82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1224): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/HtcPowerSaver(  938): updateBatteryInfo
D/NotificationService(  938): plugged=true pluggin=true
,D/UsbnetService(  938): BroadcastReceiver::onReceive+
D/UsbnetService(  938): onReceive BATTERY_CHANGED
D/UsbnetService(  938):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  938): BroadcastReceiver::onReceive-
D/WifiController(  938): handleMessage: E msg.what=155652
D/PMS     (  938): runPSCheck
D/WifiController(  938): processMsg: DeviceActiveState
D/WifiController(  938): battery changed pluggedType: 2
D/WifiController(  938): processMsg: StaEnabledState
D/HtcPowerSaver(  938): Checking...
D/WifiController(  938): processMsg: DefaultState
I/HtcPowerSaver(  938): >> updateStatus
D/WifiController(  938): handleMessage: X
D/PowerUI ( 1224): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1457): ScreenObserver: OFF
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3148): Disconnected process message: 10, size: 0
,D/NfcService( 1457): applyRouting - 0
,I/HtcPowerSaver(  938): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  938): << updateStatus
,D/PMS     (  938): acquireWL(a7a9c93): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1457 1027 null,
D/NfcService( 1457): applyRouting -2
D/NfcService( 1457): applyRouting
D/NfcService( 1457): Ignore this applyRouting...
,D/PMS     (  938): releaseWL(a7a9c93): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PowerUsageList:BatterySipperExt( 7112): gen(), null == sipper.uidObj, userId = 0,
,I/ClockController( 1224): stop clock update:screen off
,I/BatteryController( 1224): status:5 level:100 unsupport:false plugged:true,
,I/ActivityManager(  938): Killing 6695:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17,
D/Process (  938): killProcessQuiet, pid=6695
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 7112): getMobilePolicyEnabled, result = true
,E/WifiTrafficPoller(  938): ADD_CLIENT: 9
,D/WifiService(  938): New client listening to asynchronous messages
,I/ActivityManager(  938): Recipient 6695
,D/PowerUsageList:PowerUsageHelper( 7112): MY_DEBUG = false,
,D/Process (  938): killProcessQuiet, pid=6828,
I/ActivityManager(  938): Killing 6828:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  938): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,D/PMS     (  938): releaseWL(14cd7b60): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/ActivityManager(  938): Recipient 6828
,E/WifiStateMachine(  938): handleMessage: E msg.what=131155,
E/WifiStateMachine(  938): processMsg: ConnectedState
,E/WifiStateMachine(  938):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1023108883] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  938): processMsg: L2ConnectedState
,E/WifiStateMachine(  938):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1023108881] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
,E/WifiStateMachine(  938): handleMessage: X
,E/WifiStateMachine(  938): handleMessage: E msg.what=131155,
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:448] from screen [on:0 period:-1023108431] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1023108430] gl hn u24 rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  938): handleMessage: X
,D/HtcUPManager( 1224): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  938): DATA_MONITOR_POLL false Token 5,
,E/WifiDataStallTracker(  938): DATA_MONITOR_POLL false Token 5
,D/ContactMessageStore( 1438): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1438): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/ActivityManager(  938): Killing 5640:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
,D/Process (  938): killProcessQuiet, pid=5640
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  938): Recipient 5640
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/WifiStateMachine(  938): handleMessage: E msg.what=131165
E/WifiStateMachine(  938): processMsg: ConnectedState,
E/WifiStateMachine(  938):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState
E/WifiStateMachine(  938):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  938): processMsg: ConnectModeState
E/WifiStateMachine(  938):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  938): processMsg: DriverStartedState
E/WifiStateMachine(  938):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  938): processMsg: SupplicantStartedState
E/WifiStateMachine(  938):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  938): processMsg: DefaultState
E/WifiStateMachine(  938):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  938): handleMessage: X
,D/PMS     (  938): acquireWL(3e9ba4d0): PARTIAL_WAKE_LOCK  *alarm* 0x1 938 1000 WorkSource{10024},
V/AlarmManager(  938): sending alarm PendingIntent{1d5cbcc9: PendingIntentRecord{e77cfce com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141913, Int=0
,D/PMS     (  938): releaseWL(3e9ba4d0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,D/AutoSetting( 1591): service - handleMessage() stop self,
,D/AutoSetting( 1591): service - onDestroy() END
,D/AutoSetting( 1591): service - handleMessage() quit looper
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  938): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  938): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  938): acquireWL(31a86eef): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 938 1000 null,
,D/libc    (  938): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  938): [NET] android_getaddrinfofornet-, err=8
D/libc    (  938): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  938): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  938): [NET] android_getaddrinfo_proxy+
,D/libc    (  938): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  428): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  428): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  428): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  938): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  938): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  938): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  938): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  938): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  938): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  938):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  938): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  938): acquireWL(3d370b0b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 938 1000 null
D/PMS     (  938): releaseWL(31a86eef): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  938): releaseWL(3d370b0b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1438): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1438): MSG_NOTIFY_CS_TO_SYNC <<
,E/WifiStateMachine(  938): handleMessage: E msg.what=131326,
E/WifiStateMachine(  938): processMsg: ConnectedState
E/WifiStateMachine(  938):  ConnectedState what:131326 2 0
E/WifiStateMachine(  938): processMsg: L2ConnectedState,
E/WifiStateMachine(  938):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  938): handleMessage: X
,W/ContextImpl(  938): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  938): acquireWL(2b4f3de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 938 1000 null
D/UsbnetService(  938): BroadcastReceiver::onReceive+
I/BatteryService(  938): n_update end
D/UsbnetService(  938): onReceive BATTERY_CHANGED
D/PMS     (  938): releaseWL(2b4f3de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  938):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  938): plugged=true pluggin=true
,D/UsbnetService(  938): BroadcastReceiver::onReceive-
D/WifiController(  938): battery changed pluggedType: 2
D/WifiController(  938): handleMessage: E msg.what=155652
D/PowerUI ( 1224): closing low battery warning: level=100
D/WifiController(  938): processMsg: DeviceActiveState
D/WifiController(  938): processMsg: StaEnabledState
D/WifiController(  938): processMsg: DefaultState
D/WifiController(  938): handleMessage: X
I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  938): updateBatteryInfo
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  938): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  938): Checking...
D/HeadsetStateMachine( 3148): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  938): >> updateStatus
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  938): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  938): << updateStatus
,I/BatteryController( 1224): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1438): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  938): acquireWL(1f0a3c01): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 938 1000 WorkSource{1000},
,V/AlarmManager(  938): sending alarm PendingIntent{13981b11: PendingIntentRecord{3028e476 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149675, Int=0,
V/AlarmManager(  938): sending alarm PendingIntent{3f6a0aa6: PendingIntentRecord{31c94ce7 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454970855947, Int=0
V/AlarmManager(  938): sending alarm PendingIntent{29ce5094: PendingIntentRecord{fdd973d android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=200547, Int=0
V/AlarmManager(  938): sending alarm PendingIntent{3b9c2b32: PendingIntentRecord{1153d083 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189883, Int=0
D/PMS     (  938): acquireWL(3289e200): PARTIAL_WAKE_LOCK  *backup* 0x1 938 1000 null
,D/PMS     (  938): acquireWL(13916a39): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  938): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  938): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  938): releaseWL(3289e200): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  938): releaseWL(1f0a3c01): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1224): Weather sync is On,
W/WeatherTimeKeeper( 1224): [refreshWeatherData] no weather data
,D/PMS     (  938): acquireWL(45dc87e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(13916a39): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  938): releaseWL(45dc87e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  938): acquireWL(6c1f118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(6c1f118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): acquireWL(8992771): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(8992771): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): acquireWL(5a06956): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): acquireWL(13e93dd7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): acquireWL(1dc7c9ad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(5a06956): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1925): Vacuum at: now=1454970891156 tag=VacuumService,
,D/PMS     (  938): releaseWL(13e93dd7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  938): acquireWL(3399e073): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1925): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1925): No account for auth token provided
,D/PMS     (  938): releaseWL(3399e073): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  938): acquireWL(26d9cb30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(26d9cb30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1925): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1925): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1925): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1925): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1925): [NET] android_getaddrinfo_proxy+
D/libc    ( 1925): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  428): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  428): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  428): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  428): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1925): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1925): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1925): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1925): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1925): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1925): No account for auth token provided,
,W/Uploader( 1925): No account for auth token provided,
,W/Uploader( 1925):  no longer exists, so no auth token.,
,W/Uploader( 1925): No account for auth token provided,
,I/GLSUser ( 1925): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1925): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1925): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1925): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/RemoteViews( 1224): reapply : com.google.android.gms 2 40,
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1925): Failed to get auth token: User intervention required. Notification has been pushed.,
,E/Uploader( 1925): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1925): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1925): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1925): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1925): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1925): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1925): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1925): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1925): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1925): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1925): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1925): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1925): No account for auth token provided
,D/PMS     (  938): releaseWL(1dc7c9ad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  938): acquireWL(2a05a8f4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(2a05a8f4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  938): acquireWL(3e9b781d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  938): releaseWL(3e9b781d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1224): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1224): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1591): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@335a67c1,
,D/Process (  938): killProcessQuiet, pid=6633,
I/ActivityManager(  938): Killing 6633:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  938): Recipient 6633
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  938): acquireWL(a392a92): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 938 1000 null
I/BatteryService(  938): n_update end
D/PMS     (  938): releaseWL(a392a92): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1224): closing low battery warning: level=100
I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  938): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3148): Disconnected process message: 10, size: 0
D/NotificationService(  938): plugged=true pluggin=true
D/UsbnetService(  938): BroadcastReceiver::onReceive+,
D/PMS     (  938): runPSCheck
D/UsbnetService(  938): onReceive BATTERY_CHANGED
D/WifiController(  938): battery changed pluggedType: 2
D/UsbnetService(  938):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  938): Checking...
D/UsbnetService(  938): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  938): >> updateStatus
D/WifiController(  938): handleMessage: E msg.what=155652
D/WifiController(  938): processMsg: DeviceActiveState
D/WifiController(  938): processMsg: StaEnabledState
D/WifiController(  938): processMsg: DefaultState
D/WifiController(  938): handleMessage: X
,I/HtcPowerSaver(  938): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  938): << updateStatus
,I/BatteryController( 1224): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6554): --= Surplus to requirements =--
I/jxcore-log( 6554): 
,I/jxcore-log( 6554): ****TEST TOOK:  ms ****
I/jxcore-log( 6554): 
I/jxcore-log( 6554): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6554): 
,E/cutils-trace( 7184): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 7184): ====startRecUseTime====
D/htc.customization.log.level( 7184):  is 
W/CustomizationLogLevel( 7184): Level value is invalid, use default level 2
,D/CustomizationManager( 7184):  Read ACC file spent 0.045 (s)
,D/CIDMapFileReader( 7184): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7184): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 7184): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7184): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7184): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7184): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7184): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7184): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 7184): Parsing tag category name = system
,I/CustomizationCIDLoader( 7184): Parsing tag category name = application
,I/CustomizationCIDLoader( 7184): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7184): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 7184): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7184): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7184): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 7184): add string-array item, value = 42507,
I/CustomizationCIDLoader( 7184): add string-array item, value = 21902
I/CustomizationCIDLoader( 7184): add string-array item, value = 26006:26001.26002.26003,
I/CustomizationCIDLoader( 7184): add string-array item, value = 23420
I/CustomizationCIDLoader( 7184): add string-array item, value = 22299
I/CustomizationCIDLoader( 7184): add string-array item, value = 24002
I/CustomizationCIDLoader( 7184): add string-array item, value = 23210
,I/CustomizationCIDLoader( 7184): add string-array item, value = 23205
I/CustomizationCIDLoader( 7184): add string-array item, value = 23806
I/CustomizationCIDLoader( 7184): add string-array item, value = 23430
I/CustomizationCIDLoader( 7184): add string-array item, value = 23408
I/CustomizationCIDLoader( 7184): add string-array item, value = 27205,
I/CustomizationCIDLoader( 7184): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 23420:D:0:0,
I/CustomizationCIDLoader( 7184): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 23205:D:0:0
,I/CustomizationCIDLoader( 7184): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7184): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7184):  Read CID file spent 0.095 (s)
,D/CustomizationManager( 7184):  All configurations done spent 0.096 (s)
,D/PackageManager(  938): deletePackageAsUser: pkg=com.test.thalitest, pid=7184, uid=2000 userid=0,
,D/Process (  938): killProcessQuiet, pid=6554
,I/ActivityManager(  938): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
I/ActivityManager(  938): Killing 6554:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
,W/PackageSettings(  938): Skipping PackageSetting{b9ed856 com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  938): Recipient 6554
E/InputEventReceiver( 1381): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1839a38 uid 10366 pid 6554} (c)'
I/WindowState(  938): WIN DEATH: Window{266ce69b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  938): Client connection lost with reason: 4
,I/ActivityManager(  938):   Force finishing activity ActivityRecord{1a86bafd u0 com.test.thalitest/.MainActivity t8}
,I/ActivityManager(  938): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
,I/ActivityManager(  938):   Force finishing activity ActivityRecord{1a86bafd u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  938): Duplicate finish request for ActivityRecord{1a86bafd u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  938): Spurious death for ProcessRecord{43bcc63 6554:com.test.thalitest/u0a366}, curProc for 6554: null
,D/DotMatrix( 1311): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
D/PMS     (  938): acquireWL(3d4e6060): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1311): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  938): releaseWL(3d4e6060): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1840): Ignoring removeGeofence because network location is disabled.
W/SystemReader(  938): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1714): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,D/AccTypeManager( 1714): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/VoicemailCleanupService( 1679): Cleaning up data for package: com.test.thalitest
,D/PhoneApp( 1438): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1591): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/art     ( 1495): Explicit concurrent mark sweep GC freed 23516(1406KB) AllocSpace objects, 5(268KB) LOS objects, 34% free, 29MB/45MB, paused 1.013ms total 106.841ms
,D/AccTypeManager( 1714): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1495): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/[PluginManager]RegisterService( 1591): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  938): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7204 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,E/ExternalAccountType( 1714): Unsupported attribute readOnly
I/Launcher( 1495): Deferring update until onResume
,D/Launcher( 1495): waitUntilResume // bindAppsRemoved
,I/InputMethodManagerService(  938): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/ResourcesManager(  938): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/art     (  938): Explicit concurrent mark sweep GC freed 43532(2MB) AllocSpace objects, 7(1164KB) LOS objects, 33% free, 18MB/28MB, paused 1.838ms total 239.299ms,
I/art     (  938): WaitForGcToComplete blocked for 222.035ms for cause Explicit,
,D/StatusBarManagerService(  938): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  938): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  938): hiding MENU key,
D/StatusBarManagerService(  938): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  938): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ContextImpl( 7204): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  938): hiding MENU key
D/FindExtension( 1495): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1495): Defer allocateBuffers to drawing time,
,W/InputMethodManagerService(  938): Got RemoteException sending setActive(false) notification to pid 6554 uid 10366
D/StatusBarManagerService(  938): swetImeWindowStatus vis=0 backDisposition=0
,D/Process (  938): killProcessQuiet, pid=6856,
I/ActivityManager(  938): Killing 6856:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  938): Unable to load service info ResolveInfo{2ba8d7ee com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  938): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  938): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  938): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  938): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  938): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  938): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  938): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  938): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  938): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  938): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  938): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  938): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  938): Explicit concurrent mark sweep GC freed 7973(433KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/28MB, paused 1.831ms total 233.419ms,
D/JobSchedulerService(  938): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  938): Recipient 6856
W/asset   (  938): Copying FileAsset 0x559a95c6e0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/NetworkScheduler.SchedulerReceiver( 1925): Invalid parameter app
D/TaskPersister(  938): removeObsoleteFile: deleting file=8_task.xml,
E/NetworkScheduler.SchedulerReceiver( 1925): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/TaskPersister(  938): removeObsoleteFile: deleting file=8_task_thumbnail.png
I/PhoneStatusBar( 1224): setImeWindowStatus(false,false)
D/PMS     (  938): acquireWL(13fd44b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  938): releaseWL(13fd44b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PackageBroadcastService( 4440): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 4440): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded,
,I/ActivityManager(  938): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7240 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/LocationSettingsChecker( 4440): Removing dialog suppression flag for package com.test.thalitest
,D/GOOGLEHELP_CompatibleDatabase( 4440): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 4440): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4440): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4440): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4440): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 4440): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4440): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4440): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 4440): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 4440): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4440): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4440): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4440): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0,
,I/ConfigService( 1925): onCreate
I/ConfigFetchService( 4440): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  938): acquireWL(50339e0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4440 10024 null
D/PMS     (  938): releaseWL(50339e0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/PeopleContactsSync( 4440): CP2 sync disabled
,D/PMS     (  938): acquireWL(176d876a): PARTIAL_WAKE_LOCK  Icing 0x1 4440 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  938):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4440, uid=10024, userID:0
,I/Icing   ( 4440): doRemovePackageData com.test.thalitest,
D/PMS     (  938): releaseWL(176d876a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1925): Explicit concurrent mark sweep GC freed 29359(1611KB) AllocSpace objects, 9(520KB) LOS objects, 47% free, 4MB/8MB, paused 1.243ms total 66.172ms,
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,W/DriveInitializer( 4440): Awaiting to be initialized,
,W/DriveInitializer( 4440): Background init thread started,
,E/SQLiteLog( 4440): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
,E/SQLiteDBG( 4440): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x559a712950
,E/DocListDatabase( 4440): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 4440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4440): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4440): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/DocListDatabase( 4440): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4440): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4440): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/DocListDatabase( 4440): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 4440): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 4440): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,W/DriveInitializer( 4440): Background init thread ended
,E/AndroidRuntime( 4440): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4440): Process: com.google.android.gms, PID: 4440
E/AndroidRuntime( 4440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 4440): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 4440): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 4440): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/SQLiteLog( 4440): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4440): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x559a712950
,E/ActivityManager(  938): App crashed! Process: com.google.android.gms
E/DriveAsyncService( 4440): disk I/O error (code 3850)
E/DriveAsyncService( 4440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4440): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4440): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4440): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4440): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4440): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4440): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4440): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4440): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4440): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4440): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4440): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 4440): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4440): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4440): 	at java.lang.Thread.run(Thread.java:818)
,D/Process ( 4440): killProcess, pid=4440,
,D/Process ( 4440): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  938): Can't write: system_app_crash,
E/DropBoxManagerService(  938): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  938): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  938): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  938): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  938): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  938): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  938): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  938): 	,at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  938): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  938): 	... 5 more
,I/GAv4    ( 7240): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7240):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7240):   adb logcat -s GAv4,
,W/GAv4    ( 7240): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
W/GAv4    ( 7240): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7240): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/ActivityManager(  938): Recipient 4440
D/WifiService(  938): Client connection lost with reason: 4
,I/ActivityManager(  938): Process com.google.android.gms (pid 4440) has died,
W/ActivityManager(  938): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  938): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ConfigService( 1925): onDestroy
W/ActivityManager(  938): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,W/AnalyticsTrackerProxyImpl( 7240): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,E/SQLiteDatabase( 7240): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7240): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7240): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7240): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7240): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7240): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7240): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7240): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.Executors$RunnableAd,apter.call(Executors.java:422)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7240): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7240): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7240): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7240): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7240): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7240): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7240): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7240): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7240): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7240): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7240): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7240): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7240): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7240): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7240): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7240): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 7240): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7240): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7240): 	at ael.a(PG:1521),
E/SQLiteDatabase( 7240): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7240): 	at aen.run(PG:536)
,I/ActivityManager(  938): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=7282 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 7282): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7282): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7282): VM with version 2.1.0 has multidex support,
I/MultiDex( 7282): install
I/MultiDex( 7282): VM has multidex support, MultiDex support library is disabled.,
,D/VoldConnector(  938): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
D/PMS     (  938): acquireWL(3925900e): PARTIAL_WAKE_LOCK  AsyncService 0x1 6943 10167 null
,W/ContextImpl( 7240): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,D/PMS     (  938): releaseWL(3925900e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  938): acquireWL(21c8983c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6943 10167 null
,W/ResourcesManager( 7240): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7240): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SQLiteDatabase( 7240): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7240): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7240): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7240): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7240): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7240): 	at aej.c(PG:139)
E/SQLiteDatabase( 7240): 	at aej.b(PG:398)
E/SQLiteDatabase( 7240): 	at agf.f(PG:417)
E/SQLiteDatabase( 7240): 	at oe.run(PG:1112)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7240): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 7240): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7240): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7240): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7240): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7240): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7240): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7240): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7240): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7240): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7240): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7240): 	at java.lang.Thread.run(Thread.java:818)
,D/PMS     (  938): releaseWL(21c8983c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,I/UpdateIcingCorporaServi( 7009): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,V/JNIHelp ( 7240): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,E/SQLiteDatabase( 7282): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.,
E/SQLiteDatabase( 7282): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7282): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7282): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7282): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 7282): 	,at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7282): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7282): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 7282): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.,
E/SQLiteDatabase( 7282): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737),
E/SQLiteDatabase( 7282): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7282): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 7282): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.Futur,eTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7282): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7282): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  938): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=7314 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,E/SQLiteLog( 7009): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 7009): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x559a52ad10
W/System  ( 7240): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7240): Installed default security provider GmsCore_OpenSSL
,E/SQLiteDatabase( 7240): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 7240): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7240): 	at aev.getWritableDatabase(PG:238),
E/SQLiteDatabase( 7240): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7240): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7240): 	at aej.c(PG:139)
E/SQLiteDatabase( 7240): 	at aej.a(PG:358)
E/SQLiteDatabase( 7240): 	at aej.a(PG:345)
E/SQLiteDatabase( 7240): 	at agf.c(PG:884)
E/SQLiteDatabase( 7240): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 7240): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7240): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7240): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 7240): Failed to query Account133 object
E/AbstractDatabaseInstance( 7240): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7240): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7240): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7240): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7240): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7240): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 7240): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 7240): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 7240): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 7240): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 7240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7240): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 7240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7240): 	at java.lang.Thread.run(Thread.java:818)
,V/JNIHelp ( 7282): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  938): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=7340 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,E/SharedPreferencesImpl( 7009): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
E/AndroidRuntime( 7009): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 7009): Process: com.google.android.googlequicksearchbox:search, PID: 7009
E/AndroidRuntime( 7009): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7009): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 7009): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 7009): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 7009): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 7009): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 7009): ,	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 7009): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 7009): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 7009): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 7009): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
,E/AndroidRuntime( 7009): 	,at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 7009): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 7009): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 7009): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 7009): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 7009): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 7009): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7009): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7009): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7009): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  938): App crashed! Process: com.google.android.googlequicksearchbox:search,
E/DropBoxManagerService(  938): Can't write: system_app_crash
E/DropBoxManagerService(  938): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  938): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  938): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  938): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  938): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  938): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  938): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  938): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  938): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  938): 	... 5 more
D/Process ( 7009): killProcess, pid=7009
W/ActivityThread( 7282): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/Process ( 7009): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
W/System  ( 7282): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3852a3d8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7282): Installed default security provider GmsCore_OpenSSL
I/DeviceManagement( 7314): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7314 dbg=false s=true
,I/DeviceManagement( 7314): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest],
I/art     (  456): Explicit concurrent mark sweep GC freed 8678(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 287us total 33.199ms
,W/NativeLibraryUtils( 7282): Failed to open lock file,
W/NativeLibraryUtils( 7282): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7282): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7282): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
,W/NativeLibraryUtils( 7282): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7282): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7282): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7282): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7282): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7282): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7282): 	... 3 more
I/DeviceManagement( 7314): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 7314): WorkflowService: Starting workflow service
,I/DeviceManagement( 7314): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@3aee1285] args=[Bundle[mParcelledData.dataSize=112]]
,I/DeviceManagement( 7314): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 7314): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 7314): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 7314): ModelRegistry: Loading model meta data from resources...
,I/art     (  456): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 159us total 26.389ms
,I/art     (  456): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 153us total 18.239ms
,I/ActivityManager(  938): Recipient 7009
,I/DeviceManagement( 7314): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/ActivityManager(  938): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7367 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  938): Process com.google.android.googlequicksearchbox:search (pid 7009) has died
W/ActivityManager(  938): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,I/GAv4-SVC( 7282): Google Analytics 7.8.99 is starting up.,
I/DeviceManagement( 7314): SessionStateController: Checking invariants...
,W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 7240): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 7240): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/Prism.ItemManager( 1495): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1495): loadItems() com.htc.launcher.pageview.WidgetManager@43f6bff +
I/Prism.WidgetManager( 1495): onLoadItems() +
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7240): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 7282): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 7282): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7282): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7282): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 7282): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 7282): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 7282): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 7282): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 7282): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7282): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7282): 	at java.lang,.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7282): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 7282): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7282): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 7282): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 7282): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7282): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 7282): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 7282): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 7282): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 7282): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 7282): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 7282): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 7282): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 7282): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7282): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 7282): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7282): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7282): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7240): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 7240): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQL,iteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7240): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7240): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7240): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7240): 	at aen.run(PG:536)
E/GAv4    ( 7240): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/SQLiteOpenHelper( 7282): Opened reminders.db in read-only mode
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7240): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7240): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml t,o backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7240): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7240): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 7282): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7282): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7282): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7282): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7282): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.e.k.run(SourceFile:388)
W/GAv4    ( 7240): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 7282): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7240): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7282): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7240): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 7240): java.lang.RuntimeException: An error occured while executing doInBackground()
E/CAKEMIX_CRASHED( 7240): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/CAKEMIX_CRASHED( 7240): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/CAKEMIX_CRASHED( 7240): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/CAKEMIX_CRASHED( 7240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/CAKEMIX_CRASHED( 7240): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/CAKEMIX_CRASHED( 7240): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/CAKEMIX_CRASHED( 7240): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/CAKEMIX_CRASHED( 7240): 	at java.lang.Thread.run(Thread.java:818)
E/CAKEMIX_CRASHED( 7240): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 7240): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 7240): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7240): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7240): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7240): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7240): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7240): 	at aej.c(PG:139)
E/CAKEMIX_CRASHED( 7240): 	at aej.a(PG:358)
E/CAKEMIX_CRASHED( 7240): 	at aej.a(PG:345)
E/CAKEMIX_CRASHED( 7240): 	at agf.c(PG:884)
E/CAKEMIX_CRASHED( 7240): 	at aii.doInBackground(PG:1063)
E/CAKEMIX_CRASHED( 7240): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/CAKEMIX_CRASHED( 7240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/CAKEMIX_CRASHED( 7240): 	... 4 more
E/SQLiteDatabase( 7282): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7282): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7282): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7282): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7282): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.e.k.run(SourceFile:388)
E/GAv4-SVC( 7282): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7282): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 7282): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 7282): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7282): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7282): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 7282): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 7282): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7282): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7282): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7282): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 7282): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 7282): Process: com.google.android.gms, PID: 7282
E/AndroidRuntime( 7282): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 7282): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 7282): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 7282): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 7282): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 7282): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 7282): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 7282): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 7282): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 7282): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7282): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7282): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7282): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7282): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 7282): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 7282): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 7282): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 7282): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 7282): 	... 4 more
E/SharedPreferencesImpl( 7282): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  938): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 7240 on display 0
W/GAv4-SVC( 7282): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ActivityManager(  938): App crashed! Process: com.google.android.gms
E/SharedPreferencesImpl( 7282): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 7282): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7282): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 1495): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
V/ActivityManager(  938): Display changed displayId=0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/Process ( 7240): killProcess, pid=7240
D/Process ( 7240): vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  938): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 7240 on display 0
E/JavaBinder(  938): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  938): Exception thrown sending new intent to ActivityRecord{33749d1f u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t9}
W/ActivityManager(  938): android.os.TransactionTooLargeException
W/ActivityManager(  938): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  938): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  938): 	at android.app.ApplicationThreadProxy.scheduleNewIntent(ApplicationThreadNative.java:890)
W/ActivityManager(  938): 	at com.android.server.am.ActivityRecord.deliverNewIntentLocked(ActivityRecord.java:660)
W/ActivityManager(  938): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLockedImpl(ActivityStackSupervisor.java:2027)
W/ActivityManager(  938): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLocked(ActivityStackSupervisor.java:1648)
W/ActivityManager(  938): 	at com.android.server.am.ActivityStackSupervisor.startActivityLocked(ActivityStackSupervisor.java:1557)
W/ActivityManager(  938): 	at com.android.server.am.ActivityStackSupervisor.startActivityMayWait(ActivityStackSupervisor.java:972)
W/ActivityManager(  938): 	at com.android.server.am.ActivityManagerService.startActivityAsUser(ActivityManagerService.java:3757)
W/ActivityManager(  938): 	at com.android.server.am.ActivityManagerService.startActivity(ActivityManagerService.java:3744)
W/ActivityManager(  938): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:145)
W/ActivityManager(  938): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/ActivityManager(  938): 	at android.os.Binder.execTransact(Binder.java:454)
E/DropBoxManagerService(  938): Can't write: system_app_crash
E/DropBoxManagerService(  938): java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  938): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  938): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  938): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  938): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  938): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  938): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  938): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  938): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  938): 	... 5 more
D/Process ( 7282): killProcess, pid=7282
D/Process ( 7282): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/OpenGLRenderer( 1495): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
I/ActivityManager(  938): Recipient 7282
,W/GmsClient( 7340): service died
E/SilentFeedbackService( 7340): GoogleApiClient silent feedback connection failed with result: 8
,E/SQLiteDatabase( 7367): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7367): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7367): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 7367): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 7367): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 7367): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 7367): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 7367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 7367): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 7367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 7367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7367): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7367): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7367): 	,at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7367): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/AndroidRuntime( 7367): FATAL EXCEPTION: main
E/AndroidRuntime( 7367): Process: com.android.documentsui, PID: 7367
E/AndroidRuntime( 7367): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 7367): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 7367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 7367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7367): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7367): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7367): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7367): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7367): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7367): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7367): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 7367): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 7367): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 7367): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 7367): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 7367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 7367): 	... 9 more
,E/SQLiteDatabase( 7314): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7314): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7314): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7314): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 7314): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 7314): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 7314): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 7314): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7314): 	,at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 7314): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7314): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 7314): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7314): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 7314): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 7314): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 7314): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7314): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7314): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7314): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  938): Recipient 7240
,I/ActivityManager(  938): Process com.google.android.gms (pid 7282) has died
,W/ActivityManager(  938): Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 10745ms
W/ActivityManager(  938): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20745ms
,I/ActivityManager(  938): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7398 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,W/HtcSystemUPManager(  938): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  938): Process com.google.android.apps.docs (pid 7240) has died
,W/ResourcesManager( 1495): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  938): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=7418 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
E/ActivityManager(  938): App crashed! Process: com.android.documentsui
,I/DeviceManagement( 7314): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,D/ErrorReport(  938): HtcErrorReportManager Begin---add error logs to dropbox
,I/DeviceManagement( 7314): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 7314): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,W/System.err(  938): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  938): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  938): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  938): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  938): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  938): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  938): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  938): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  938): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  938): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  938): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  938): 	at libcore.io.Posix.open(Native Method)
W/System.err(  938): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  938): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  938): 	... 12 more
,E/SQLiteDatabase( 7314): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 7314): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7314): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7314): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7314): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 7314): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/SQLiteDatabase( 7314): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 7314): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 7314): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 7314): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 7314): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7314): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7314): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 7314): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@3aee1285]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/Device,Management( 7314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/DeviceManagement( 7314): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
W/DeviceManagement( 7314): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/DeviceManagement( 7314): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 7314): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/DeviceManagement( 7314): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 7314): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 7314): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 7314): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 7314): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 7314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 7314): 	at android.os.Looper.loop(Looper.java:155)
W/DeviceManagement( 7314): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  938): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  938): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  938): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  938): 	at com.htc.server.report.error.Er,rorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  938): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  938): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  938): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  938): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  938): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  938): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  938): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  938): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  938): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  938): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  938): 	at libcore.io.Posix.open(Native Method)
W/System.err(  938): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  938): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  938): 	... 14 more
W/System.err(  938): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  938): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  938): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  938): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  938): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  938): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
I/ActivityManager(  938): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7434 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a
W/System.err(  938): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  938): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  938): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  938): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  938): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  938): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  938): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  938): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  938): 	at libcore.io.Posix.open(Native Method)
W/System.err(  938): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  938): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  938): 	... 14 more
I/DeviceManagement( 7314): WorkflowService: Stopping workflow service
I/ActivityManager(  938): Killing 6919:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  938): killProcessQuiet, pid=6919
D/Process (  938): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager( 7398): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/ErrorReport(  938): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  938): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454970969904.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  938): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  938): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  938): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  938): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  938): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  938): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  938): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  938): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  938): 	... 4 more
,W/asset   ( 1495): Copying FileAsset 0x559a83e500 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1495): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1495): onLoadItems() -
I/Prism.ItemManager( 1495): loadItems() com.htc.launcher.pageview.WidgetManager@43f6bff -
,I/ActivityManager(  938): Recipient 6919,
,E/SQLiteLog( 1495): (3850) statement aborts at 16: [DELETE FROM externalapp WHERE package_name='com.test.thalitest'] disk I/O error,
E/SQLiteDBG( 1495): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/externalapp.db, handle: 0x559a4ee020
,W/System.err( 1495): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,W/System.err( 1495): ,	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 1495): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
W/System.err( 1495): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 1495): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 1495): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
W/System.err( 1495): 	at com.htc.launcher.ExternalAppStateProvider.delete(ExternalAppStateProvider.java:71)
W/System.err( 1495): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
W/System.err( 1495): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
W/System.err( 1495): ,	at com.htc.launcher.ExternalAppStateList$1.run(ExternalAppStateList.java:147)
W/System.err( 1495): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
W/System.err( 1495): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
W/System.err( 1495): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1495): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 1495): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1495): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=75] disk I/O error,
E/SQLiteDBG( 1495): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0x559a503550

```
