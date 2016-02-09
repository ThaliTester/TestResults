#### Test 583805004f2b042_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  944): acquireWL(4c596e9): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10072}
V/AlarmManager(  944): sending alarm PendingIntent{1d526f6e: PendingIntentRecord{3721260f com.android.vending startService}}, i=null, t=0, cnt=1, w=1455035787474, Int=0
--------- beginning of main
V/CheckinService( 4464): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
V/AlarmManager(  944): sending alarm PendingIntent{114ff69c: PendingIntentRecord{14d7b8a5 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455035790329, Int=536832000
V/AlarmManager(  944): sending alarm PendingIntent{289af365: PendingIntentRecord{2540983a android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455035783339, Int=20000
D/PMS     (  944): acquireWL(eba147a): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4464 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  944): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944): handleMessage: E msg.what=131143
D/PMS     (  944): releaseWL(4c596e9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:56 rssi=-67 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=2.1 list=2412 [on:0 tx:0 rx:0 period:2354] from screen [on:0 period:-958122984]
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:56 rssi=-67 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=2.1 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-958122983]
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.39 rxSuccessRate=2.07 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-67
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN with age=58663 interval=60000 maxinterval=300000
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  944): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  944): has c0:ff:d4:d3:aa:48 freq=2412 age=2360 ?=true
E/WifiStateMachine(  944): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1330): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x559ee190f0
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x559ee190f0 after 0.000037 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000092 seconds
D/PMS     (  944): acquireWL(37b3e088): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4464 10024 WorkSource{10024 com.google.android.gms}
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  944): [1,455,035,790,364 ms] noteScanstart no scan source
E/WifiStateMachine(  944): handleMessage: X
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  944): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  944): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/PMS     (  944): releaseWL(eba147a): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4464): Checking schedule, now: 1455035790389 next: 1455035790329
I/CheckinService( 4464): active receiver: enabled
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4464, uid=10024, userID:0
I/CheckinService( 4464): Preparing to send checkin request
I/EventLogService( 4464): Accumulating logs since 1455035756010
D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.074276 seconds
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-53
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-67
I/wpa_supplicant( 1330): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-84
I/wpa_supplicant( 1330): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1330): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 1330): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x559ee190f0 done in 0.075220 seconds
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
I/ActivityManager(  944): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/WifiMonitor(  944): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/ActivityThread( 4464): Failed to find provider info for com.google.android.wearable.settings
E/WifiStateMachine(  944): handleMessage: E msg.what=147461
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  944): processMsg: DriverStartedState
E/WifiStateMachine(  944):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  944): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/CheckinRequestBuilder( 4464): Checkin reason type: 11 attempt count: 1
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  944): [1,455,035,790,442 ms] noteScanEnd no scan source
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  944): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@f9e8903 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  944): NG7005g c0:ff:d4:d3:aa:4a rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): NG700 c0:ff:d4:d3:aa:48 rssi=-67 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  944): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  944): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  944):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-67 freq=2412
E/WifiAutoJoinController (  944): UPC503894600 a0:c5:62:7a:49:97 rssi=-84 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  944): ageScanResultsOut delay 40000 size 4 now 1455035790446
E/WifiAutoJoinController (  944): newSupplicantResults size=4 known=1 true
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
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
E/WifiAutoJoinController (  944): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-67,-127) num=(1,0)
E/WifiAutoJoinController (  944): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  944): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-67 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  944): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  944): Done attemptAutoJoin status=0
E/WifiConfigStore(  944):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  944): handleMessage: X
I/HtcModeClient( 3251): handler message = 4011
E/HtcModeClient( 3251): Check connection and retry 11 times.
E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  944):  packet count Tx=135 Rx=221
D/WIFI_ICON( 1220): WifiActivity: 1
E/WifiTrafficPoller(  944): notifying of data activity 1
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/Finsky  ( 5944): [602] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5944): [1] 5.onFinished: Installation state replication succeeded.
I/art     (  944): Explicit concurrent mark sweep GC freed 39524(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/25MB, paused 1.886ms total 183.004ms
I/GLSUser ( 1958): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1958): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1958): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1958): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/CheckinRequestBuilder( 4464): awaiting user notification for token
I/RemoteViews( 1220): reapply : com.google.android.gms 3 40
D/DotMatrix( 1339): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1339): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/ActivityManager(  944): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6312 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 6312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6312): VM with version 2.1.0 has multidex support
I/MultiDex( 6312): install
I/MultiDex( 6312): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 6312): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6312): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c5e1153: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6312): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1958): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/WifiStateMachine(  944): handleMessage: E msg.what=131155
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:642] from screen [on:0 period:-958122338] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-958122337] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
D/AuthorizationBluetoothService( 1958): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4464): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -67 abnormalRssiCnt = 0 newLinkSpeed = 57
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-67 linkspeed=57
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-67 "NG700"WPA_PSK
E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.19 txretriesrate=0.00 rxrate=2.54 userTriggerdPenalty0
E/WifiStateMachine(  944):  good link -> stuck count =0
E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  944):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -67, 3
E/WifiStateMachine(  944): handleMessage: X
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WearableService( 4822): callingUid 10024, callindPid: 4822
E/MDM     ( 1837): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4464, uid=10024, userID:0
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
D/LocationInitializer( 4464): Restart initialization of location
D/QSEECOMAPI: (  401): Loaded image: APP id = 8
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4a28000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4a28000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  495): got the req here! ret=0
D/DrmLibTime(  495): command id, time_cmd_id = 770
D/DrmLibTime(  495): time_getutcsec starts!
D/DrmLibTime(  495): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  495): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  495): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  495): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  495): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  495): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  495): QSEE Time Listener: Retrieved Android system time: 1455035791
D/DrmLibTime(  495): time_getutcsec returns 0, sec = 1455035791; nsec = 0
D/DrmLibTime(  495): time_getutcsec finished! 
D/DrmLibTime(  495): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  495): before calling ioctl to read the next time_cmd
E/QC-time-services(  429): Daemon: Time-services: Waiting to acceptconnection
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
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4b52928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xaafe98e0, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab0e44c8, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xaafce888, idLength=0xffd8d7c8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xffd8d7de, maximum = 0xffd8d7df
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffd8d84c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=2852091042
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab053a50
D/DrmWidevineDash(  401): message_length=1611, signature=0xab0540a0, signature_length=0xffd8d7ac
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/cutils-trace( 6336): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6336): ====startRecUseTime====
D/htc.customization.log.level( 6336):  is 
W/CustomizationLogLevel( 6336): Level value is invalid, use default level 2
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
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
D/CustomizationManager( 6336):  Read ACC file spent 0.037 (s)
D/CIDMapFileReader( 6336): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6336): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6336): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6336): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6336): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6336): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6336): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6336): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6336): Parsing tag category name = system
I/CustomizationCIDLoader( 6336): Parsing tag category name = application
I/CustomizationCIDLoader( 6336): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6336): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6336): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6336): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6336): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6336): add string-array item, value = 42507
I/CustomizationCIDLoader( 6336): add string-array item, value = 21902
I/CustomizationCIDLoader( 6336): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6336): add string-array item, value = 23420
I/CustomizationCIDLoader( 6336): add string-array item, value = 22299
I/CustomizationCIDLoader( 6336): add string-array item, value = 24002
I/CustomizationCIDLoader( 6336): add string-array item, value = 23210
I/CustomizationCIDLoader( 6336): add string-array item, value = 23205
I/CustomizationCIDLoader( 6336): add string-array item, value = 23806
I/CustomizationCIDLoader( 6336): add string-array item, value = 23430
I/CustomizationCIDLoader( 6336): add string-array item, value = 23408
I/CustomizationCIDLoader( 6336): add string-array item, value = 27205
I/CustomizationCIDLoader( 6336): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6336): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6336):  Read CID file spent 0.075 (s)
D/CustomizationManager( 6336):  All configurations done spent 0.076 (s)
I/ActivityManager(  944): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6336 on display 0
D/PMS     (  944): acquireHCC(cd87593): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 944 1000 null
D/PMS     (  944): acquireHCC(2eaf09d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 944 1000 null
W/asset   (  944): Copying FileAsset 0x559ec84960 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  944): acquireWL(3e8ad7ef): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 944 1000 null
I/AnimationUtil(  944): isHTCRecent(ThaliTest/Recent screens.)/6
I/FeedHostManager( 1577): [onPause]
I/FeedProviderManager( 1577): onPause
I/FeedHostManager( 1577): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@80e955f
I/SocialFeedProvider( 1577): +onPause
I/SocialFeedProvider( 1577): -onPause
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
E/cutils-trace( 6359): Error opening trace file: Permission denied (13)
I/dex2oat ( 6359): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6359): dex2oat: override thread count:4
I/ActivityManager(  944): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6361 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/dex2oat ( 6359): dex2oat took 46.673ms (threads: 4)
I/Adreno-EGL( 6312): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6312): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6312): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6312): Local Branch: 
I/Adreno-EGL( 6312): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6312): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6312):                  d74aa161a12b9c6fc6332151
D/StatusBarManagerService(  944): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
W/asset   ( 6361): Copying FileAsset 0xaca00398 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  944):  packet count Tx=135 Rx=221
E/WifiTrafficPoller(  944): notifying of data activity 0
D/WIFI_ICON( 1220): WifiActivity: 0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/TrimMemoryManager( 1577): [trimMemory] 20
I/Adreno-EGL( 6312): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6312): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6312): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6312): Local Branch: 
I/Adreno-EGL( 6312): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6312): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6312):                  d74aa161a12b9c6fc6332151
,I/WVCdm   (  401): CdmEngine::OpenSession
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
I/WebViewFactory( 6361): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/QSEECOMAPI: (  401): Loaded image: APP id = 9
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4a28000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4a28000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  495): got the req here! ret=0
D/DrmLibTime(  495): command id, time_cmd_id = 770
D/DrmLibTime(  495): time_getutcsec starts!
D/DrmLibTime(  495): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  495): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  495): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  495): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  495): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  495): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  495): QSEE Time Listener: Retrieved Android system time: 1455035791
D/DrmLibTime(  495): time_getutcsec returns 0, sec = 1455035791; nsec = 0
D/DrmLibTime(  495): time_getutcsec finished! 
D/DrmLibTime(  495): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  495): before calling ioctl to read the next time_cmd
E/QC-time-services(  429): Daemon: Time-services: Waiting to acceptconnection
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
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4b52928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xaaff7ca8, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaafc7ce8, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xaafce8a8, idLength=0xf4c526f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4c5270e, maximum = 0xf4c5270f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/LibraryLoader( 6361): Time to load native libraries: 15 ms (timestamps 7847-7862)
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4c5277c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=65334007
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaafb4f28
D/DrmWidevineDash(  401): message_length=1645, signature=0xaafcede8, signature_length=0xf4c526dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/LibraryLoader( 6361): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6361): Binding Chromium to main looper Looper (main, tid 1) {13898ba6}
I/LibraryLoader( 6361): Expected native library version number "",actual native library version number ""
I/chromium( 6361): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6361): Initializing chromium process, singleProcess=true
W/art     ( 6361): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6361): ApplicationContext is null in ApplicationStatus
W/chromium( 6361): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
I/Adreno-EGL( 6361): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6361): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6361): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6361): Local Branch: 
I/Adreno-EGL( 6361): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6361): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6361):                  d74aa161a12b9c6fc6332151
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
W/System.err(  944): java.lang.Throwable: stack dump
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
I/CheckinRequestBuilder( 4464): Classify the device as Phone.
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1427132c:true
D/BluetoothAdapter( 6361): 369449728: getState(). Returning 12
D/libc    ( 4464): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4464): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4464): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4464): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4464): [NET] android_getaddrinfo_proxy+
D/libc    ( 4464): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4464): [NET] android_getaddrinfo_proxy-, success
W/art     ( 6361): Attempt to remove local handle scope entry from IRT, ignoring
D/libc    ( 4464): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4464): [NET] android_getaddrinfofornet-, err=8
W/AwContents( 6361): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6361): CordovaWebView is running on device made by: HTC
W/art     ( 6361): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6361): Attempt to remove local handle scope entry from IRT, ignoring
D/libc    ( 4464): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4464): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4464): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4464): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4464): Sending checkin request (8442 bytes)
W/chromium( 6361): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6361): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6361): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4ccdd73, mServedView=org.apache.cordova.engine.SystemWebView{30a58430 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@11e018a9
I/InputMethodManagerService(  944): Disable input method client, pid=1577
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  944): Enable input method client, pid=6361
I/ActivityManager(  944): Displayed com.test.thalitest/.MainActivity: +823ms
D/PMS     (  944): releaseWL(3e8ad7ef): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
W/BindingManager( 6361): Cannot call determinedVisibility() - never saw a connection for the pid: 6361
W/XT9_C   ( 1383): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1383): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1383): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1383): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/JsMessageQueue( 6361): Set native->JS mode to OnlineEventsBridgeMode
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  944):  packet count Tx=150 Rx=231
D/WIFI_ICON( 1220): WifiActivity: 3
E/WifiTrafficPoller(  944): notifying of data activity 3
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/jxcore_app_log( 6361): JniHelper::setJavaVM(0xab8948f8), pthread_self() = -1396967968
,I/chromium( 6361): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  944): updateDataStallInfo: mDataStallTxRxSum={txSum=133 rxSum=119} preTxRxSum={txSum=118 rxSum=109}
D/WifiDataStallTracker(  944): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  944): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/PMS     (  944): releaseHCC(cd87593): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  944): releaseHCC(2eaf09d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6361): Initializing JXcore engine
,W/jxcore-log( 6361): JXcore engine is ready
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  944):  packet count Tx=150 Rx=231
E/WifiTrafficPoller(  944): notifying of data activity 0
D/WIFI_ICON( 1220): WifiActivity: 0
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/CheckinRequestBuilder( 4464): Checkin reason type: 11 attempt count: 1,
I/ActivityManager(  944): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4464): Failed to find provider info for com.google.android.wearable.settings
W/jxcore-log( 6361): Starting JXcore engine
,W/jxcore-log( 6361): Platform android
W/jxcore-log( 6361): 
W/jxcore-log( 6361): Process ARCH arm
W/jxcore-log( 6361): 
,I/GLSUser ( 1958): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1958): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1958): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1958): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1339): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1339): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 4464): awaiting user notification for token
,I/RemoteViews( 1220): reapply : com.google.android.gms 1 40,
,I/CheckinRequestBuilder( 4464): Classify the device as Phone.,
,I/CheckinTask( 4464): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4464): Checking schedule, now: 1455035793918 next: 1455572625910,
I/CheckinService( 4464): active receiver: disabled
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4464, uid=10024, userID:0
,D/PMS     (  944): releaseWL(37b3e088): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6431 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/PhoneMonitor( 6431): Register our PhoneStateListener
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155
E/WifiStateMachine(  944): processMsg: ConnectedState
,E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=0.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-958119315] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
V/SetupWizard( 6431): Connected to Gservices successfully
,E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=0.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-958119314] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=16 [18][3][0]
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -67 abnormalRssiCnt = 0 newLinkSpeed = 57
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-67 linkspeed=57
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-67 "NG700"WPA_PSK
E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.10 txretriesrate=0.00 rxrate=8.77 userTriggerdPenalty0
E/WifiStateMachine(  944):  good link -> stuck count =0
E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  944):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -67, 3
E/WifiStateMachine(  944): handleMessage: X
,D/ChimeraCfgMgr( 4464): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4464): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 6431): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/GCM     ( 1958): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PhoneMonitor( 6431): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/jxcore-log( 6361): JXcore Cordova bridge is ready!,
I/jxcore-log( 6361): 
W/jxcore-log( 6361): JXcore engine is started
,E/jxcore  ( 6361): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6361): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6361): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PMS     (  944): acquireWL(391dbcb7): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 944 1000 null
W/PluginManager( 6361): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 63ms. Plugin should use CordovaInterface.getThreadPool().
,W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,I/FeedHostManager( 1577): [onResume],
I/FeedProviderManager( 1577): onResume
I/SocialFeedProvider( 1577): +onResume
I/SocialFeedProvider( 1577): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1577): -onResume
,D/StatusBarManagerService(  944): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
,D/FindExtension( 1577): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1577): Defer allocateBuffers to drawing time
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
I/InputMethodManagerService(  944): Disable input method client, pid=6361
W/IInputConnectionWrapper( 6361): reportFullscreenMode on inactive InputConnection
,D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  944): Enable input method client, pid=1577
,D/PMS     (  944): releaseWL(391dbcb7): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  944): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=153 Rx=236
D/WIFI_ICON( 1220): WifiActivity: 3
E/WifiTrafficPoller(  944): notifying of data activity 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/OpenGLRenderer( 1577): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/HtcModeClient( 3251): handler message = 4011,
E/HtcModeClient( 3251): Check connection and retry 12 times.
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=153 Rx=238
E/WifiTrafficPoller(  944): notifying of data activity 1
D/WIFI_ICON( 1220): WifiActivity: 1
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Process (  944): killProcessQuiet, pid=5781,
I/ActivityManager(  944): Killing 5781:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5781
,I/ActivityManager(  944): Killing 4563:com.google.android.talk/u0a112 (adj 15): empty #17,
,D/Process (  944): killProcessQuiet, pid=4563
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4563
,D/Process (  944): killProcessQuiet, pid=5828
I/ActivityManager(  944): Killing 5828:com.htc.calendar/u0a10 (adj 15): empty #18
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5828
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1220): WifiActivity: 3,
E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=239
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  944): notifying of data activity 3
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155
,E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=9.1, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-958116306] gl hn u24 rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=9.1, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-958116305] gl hn u24 rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [2][0][0]
,E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -66 abnormalRssiCnt = 0 newLinkSpeed = 57
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-66 linkspeed=57
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-66 "NG700"WPA_PSK
,E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.55 txretriesrate=0.00 rxrate=5.88 userTriggerdPenalty0
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  944):  good link -> stuck count =0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  944):  isHighRSSI       ---> score=65
E/WifiStateMachine(  944): handleMessage: X
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -66, 3
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1220): WifiActivity: 0
,E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=239
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  944): notifying of data activity 0
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  944): updateDataStallInfo: mDataStallTxRxSum={txSum=138 rxSum=125} preTxRxSum={txSum=133 rxSum=119}
D/WifiDataStallTracker(  944): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  944): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=239
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1220): WifiActivity: 1
E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=240
E/WifiTrafficPoller(  944): notifying of data activity 1
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155,
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=5.5, 0.0, 0.0  rx=5.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-958113288] gl hn u24 rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=5.5, 0.0, 0.0  rx=5.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-958113286] gl hn u24 rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0],
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -67 abnormalRssiCnt = 0 newLinkSpeed = 57
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-67 linkspeed=57,
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-66 "NG700"WPA_PSK
E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.77 txretriesrate=0.00 rxrate=3.44 userTriggerdPenalty0
E/WifiStateMachine(  944):  good link -> stuck count =0
E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  944):  isHighRSSI       ---> score=61
E/WifiStateMachine(  944): handleMessage: X,
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -67, 3
,I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,W/Prism.AllAppsManager( 1577): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1743): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/ActivityManager(  944): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6459 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
W/SystemReader(  944): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1743): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  944): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/art     (  409): Explicit concurrent mark sweep GC freed 8690(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 362us total 28.529ms
,D/PhoneApp( 1534): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
D/AccTypeManager( 1743): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 278us total 22.501ms
,E/ExternalAccountType( 1743): Unsupported attribute readOnly
,I/HtcModeClient( 3251): handler message = 4011
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 316us total 17.028ms
,E/HtcModeClient( 3251): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3251): Don't start project servcice
D/HtcModeClient( 3251): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3251): connectState: CONNECTION_READY = false
D/SilentMusic( 3251): call stop
D/HtcModeClient( 3251): close connection
W/HtcModeClient( 3251): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3251): read the terminate packet, so break
,D/Process (  944): killProcessQuiet, pid=3251
I/ActivityManager(  944): Killing 3251:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  944): Unable to load service info ResolveInfo{105665a1 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  944): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
,W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
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
,I/BackupManagerService(  944): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/ActivityManager(  944): Recipient 3251
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=240
D/WIFI_ICON( 1220): WifiActivity: 0
E/WifiTrafficPoller(  944): notifying of data activity 0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/GmsNetworkLocationProvi( 1837): DISABLE,
,I/GCoreNlp( 1837): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  944): applying state to connected service,
D/PMS     (  944): acquireWL(3e255ac5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1837 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3e255ac5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  944): applying state to connected service,
,D/PMS     (  944): acquireWL(10eddc1a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1837 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(10eddc1a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(472d34b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1837 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(472d34b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): acquireWL(18470128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1837 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(18470128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6459): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6459): MmsConfig.loadMmsSettings
,I/ActivityManager(  944): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6488 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6459, uid=10112, userID:0
,W/HtcWrapAdjustableCursorFactory( 6488): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 6488): onCreate
,I/art     (  944): Explicit concurrent mark sweep GC freed 30581(1682KB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 18MB/28MB, paused 1.525ms total 163.651ms,
D/MmsCustomizationProvider( 6488): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 6488): GetPrviateResource
V/GetPrviateResource( 6488): GetPrviateResource
W/Settings( 6459): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MessageCustFlag( 6488): sense_version=6.0
D/BTAccessoryUtil( 6488): createReceiver
I/Babel_Crash( 6459): startup - clean
D/MmsCustomizationProvider( 6488): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/BTAccessoryUtil( 6488): registerReceiver return intent = null
D/MessageCustFlag( 6488): sku_id=118
I/Babel_SMS( 6459): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6459): MmsConfig.loadFromDatabase
D/HtcBuildUtils( 6488): getRATByHtcTelephonyCapability:1
W/SystemReader( 6488): Cannot find qct_8960_interface, use default value instead
E/Babel_SMS( 6459): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6459): MmsConfig.loadFromResources
,E/Babel_SMS( 6459): canonicalizeMccMnc: invalid mccmnc nullnull,
I/Babel_SMS( 6459): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel   ( 6459): deleted: false for 0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6459, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6459, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6459, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6459, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6459, uid=10112, userID:0
,D/PMS     (  944): acquireWL(1b61d9b1): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6459 10112 null,
,W/VideoCapabilities( 6459): Unrecognized profile 2130706433 for video/avc
,I/[PluginManager]RegisterService( 1638): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1638): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4464): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/PMS     (  944): acquireWL(1c6300b3): PARTIAL_WAKE_LOCK  AsyncService 0x1 6013 10167 null
I/PackageBroadcastService( 4464): Null package name or gms related package.  Ignoreing.
D/PMS     (  944): releaseWL(1c6300b3): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  944): acquireWL(4ee1a6e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6013 10167 null
,D/PMS     (  944): acquireWL(482f50f): PARTIAL_WAKE_LOCK  Icing 0x1 4464 10024 WorkSource{10024 com.google.android.gms}
,W/VideoCapabilities( 6459): Unsupported mime video/x-ms-wmv
D/PMS     (  944): releaseWL(4ee1a6e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
I/Icing   ( 4464): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 5866): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Utils   ( 6459): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 6459): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6459): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6459): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6459): Unsupported mime video/x-ms-wmv
D/PMS     (  944): releaseWL(482f50f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/VideoCapabilities( 6459): Unsupported profile 4 for video/mp4v-es
,I/UpdateIcingCorporaServi( 5866): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
,W/VideoCapabilities( 6459): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6459): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6459): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6459): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 6459): onServiceConnected,
W/Babel   ( 6459): Attempted to change video mute state without an active call.
,D/PMS     (  944): releaseWL(1b61d9b1): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null,
,W/ResourcesManager( 6459): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6459): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6459): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6459): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6459): Installed default security provider GmsCore_OpenSSL
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=241
D/WIFI_ICON( 1220): WifiActivity: 1
,E/WifiTrafficPoller(  944): notifying of data activity 1
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Prism.ItemManager( 1577): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1577): loadItems() com.htc.launcher.pageview.WidgetManager@2e8a59ef +
I/Prism.WidgetManager( 1577): onLoadItems() +
,E/Prism.WidgetManager( 1577): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1577): onLoadItems() -
I/Prism.ItemManager( 1577): loadItems() com.htc.launcher.pageview.WidgetManager@2e8a59ef -
,D/PhoneApp( 1534): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1534): -- N1 =0
,D/PhoneApp( 1534): -- N2 =0
,D/PhoneApp( 1534): -- N3 =0,
,I/ActivityManager(  944): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6527 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  944): acquireWL(8030034): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10076}
V/AlarmManager(  944): sending alarm PendingIntent{2f8f1e5d: PendingIntentRecord{341e73d2 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455035802702, Int=60000,
,D/PMS     (  944): releaseWL(8030034): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6527): SMSBackupAgentService started,
D/SMSBackup( 6527): Checking restore status,
,D/SMSBackup( 6527): Restore complete,
D/SMSBackup( 6527): cancelCheckAlarm
,D/SMSBackup( 6527): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  944): killProcessQuiet, pid=5898,
I/ActivityManager(  944): Killing 5898:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=241
E/WifiTrafficPoller(  944): notifying of data activity 0
D/WIFI_ICON( 1220): WifiActivity: 0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  944): Recipient 5898
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155,
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=2.8, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-958110264] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
,E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=2.8, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-958110262] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944):  get link layer stats 0,
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -67 abnormalRssiCnt = 0 newLinkSpeed = 57
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-67 linkspeed=57
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-66 "NG700"WPA_PSK
E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.39 txretriesrate=0.00 rxrate=2.22 userTriggerdPenalty0
E/WifiStateMachine(  944):  good link -> stuck count =0
E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  944):  isHighRSSI       ---> score=61
E/WifiStateMachine(  944): handleMessage: X
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -67, 3
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  944): updateDataStallInfo: mDataStallTxRxSum={txSum=138 rxSum=125} preTxRxSum={txSum=138 rxSum=125}
D/WifiDataStallTracker(  944): updateDataStallInfo: NONE
D/WifiDataStallTracker(  944): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,D/Messaging( 6488): supportCMAS(SIE)/init? false/true,
,D/MmsConfig( 6488): networkCode: 
D/MessageCustFlag( 6488): sku_id=118
D/MmsConfig( 6488): SIE smsPri: null,
D/MmsConfig( 6488): networkCode: 
,D/MmsConfig( 6488): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6488): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 6488): ,
D/MmsAsyncWorkHandler( 6488): HM tk = 20001
D/ReportIndicatorCache( 6488): MSG_QUERY_REPORTS >>
D/SettingsManager( 6488): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@228139e7
,D/Messaging( 6488): mNeedToUpdateDate2 start
,D/DraftCache( 6488): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 6488): [DraftCache/1] refresh
,D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83,
D/MmsSmsV2Provider( 1534):  slotId = -1000
D/MmsSmsV2Provider( 1534): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1534): sku_id=118
,I/Messaging( 6488): mccmnc> ,
D/DraftCache( 6488): [DraftCache/156] rebuildCache
D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1534):  slotId = -1000
D/MmsSmsV2Provider( 1534): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/MmsSmsV2Provider( 1534):  slotId = -1000
D/MmsSmsV2Provider( 1534): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MmsConfig( 6488): networkCode: 
,D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1534):  slotId = -1000
D/MmsSmsV2Provider( 1534): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6488): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Messaging( 6488): mNeedToUpdateDate2: false
,D/Messaging( 6488): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83,
D/Jerry   ( 1534): URI_DRAFT
,D/DraftCache( 6488): hasDraft() = false mNeedNotifyChange = true,
D/DraftCache( 6488): [DraftCache/156] rebuildCache time: 12
D/MmsAsyncWorkHandler( 6488): 
D/MmsAsyncWorkHandler( 6488): HM tk = 20002
,D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MessageCustFlag( 6488): sense_version=6.0
D/Jerry   ( 6488): start to preload cursor >>>>>>>
,D/AccFlag ( 1534): sku_id=118
D/PhoneStorageUtil( 6488): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6488): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6488): createReceiver
,D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1534):  slotId = -1000
,D/TelephUtils( 1534): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
V/MmsProvider( 1534): Update uri=content://mms, match=0
V/MmsProvider( 1534): selection=st=129 AND m_type!=134
,D/Messaging( 6488): Reset downloading state: 0
V/MmsSystemEventReceiver( 6488): TransactionService is going to be woken up.
,D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1534): sku_id=118
,D/Messaging( 6488): ViewCache CreatePreload,
D/Messaging( 6488): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 6488): 1-Creating TransactionService
,D/Cust_MMSMS( 6488): _has_set_default_values_2=true,
,V/TransactionService( 6488): onStartCommand: 1
,D/MmsSystemEventReceiver( 6488): unRegisterForConnectionStateChanges
,V/TransactionService( 6488): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6488): Loading previous transactions.
,D/MsgPreferenceUtils( 6488): def_index: 0,
D/TelephUtils( 1534): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/AccFlag ( 1534): device_type: 1
D/MsgPreferenceUtils( 6488): globalIndex = 1
,D/TransactionService( 6488): Force clearing mTransactionList
D/TransactionService( 6488): Force set service start id to 1
,V/TransactionService( 6488): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6488): unRegisterForConnectionStateChanges
D/MsgPreferenceUtils( 6488): phone state: true
D/MsgPreferenceUtils( 6488): sd state: false
D/MsgPreferenceUtils( 6488): vIndex = 0
,V/TransactionService( 6488): Destroying TransactionService
D/TransactionService( 6488): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 6488): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
D/PMS     (  944): acquireWL(3f6004e7): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000}
,V/AlarmManager(  944): sending alarm PendingIntent{289af365: PendingIntentRecord{2540983a android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455035803339, Int=20000
,E/WifiStateMachine(  944): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  944): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944): processMsg: ConnectedState
D/PMS     (  944): releaseWL(3f6004e7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  944):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:78 rssi=-67 f=2412 sc=60 link=57 tx=1.4, 0.0, 0.0  rx=2.2 list=2412 [on:0 tx:0 rx:0 period:241] from screen [on:0 period:-958110003]
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:78 rssi=-67 f=2412 sc=60 link=57 tx=1.4, 0.0, 0.0  rx=2.2 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-958110002]
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.39 rxSuccessRate=2.22 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-67
,E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN with age=71644 interval=60000 maxinterval=300000
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN try full band scan age=71644 interval=60000 maxinterval=300000
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  944): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
,D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1330): WPS:  * Manufacturer
,D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x559edf5860
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x559edf5860 after 0.000032 second wait
,D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000076 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  944): [1,455,035,803,344 ms] noteScanstart no scan source
E/WifiStateMachine(  944): handleMessage: X
,D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  944): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  944): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=241
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=241
,D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available,
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 2.066042 seconds
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-67
I/wpa_supplicant( 1330): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1330): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1330): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x559edf5860 done in 2.066955 seconds
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  944): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  944): handleMessage: E msg.what=147461
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  944): processMsg: DriverStartedState
E/WifiStateMachine(  944):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  944): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  944): [1,455,035,805,417 ms] noteScanEnd no scan source
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  944): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@f9e8903 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  944): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): NG700 c0:ff:d4:d3:aa:48 rssi=-67 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  944): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  944): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  944):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-67 freq=2412
E/WifiAutoJoinController (  944): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  944): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  944): ageScanResultsOut delay 40000 size 4 now 1455035805421
E/WifiAutoJoinController (  944): newSupplicantResults size=4 known=1 true
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  944): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
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
E/WifiAutoJoinController (  944): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-67,-127) num=(1,0)
E/WifiAutoJoinController (  944): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  944): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-67 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  944): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  944): Done attemptAutoJoin status=0
E/WifiConfigStore(  944):  writeKnownNetworkHistory() num networks:1 needWrite=false
,E/WifiStateMachine(  944): handleMessage: X
D/WifiManager( 1837): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=241
,D/Process (  944): killProcessQuiet, pid=6196
I/ActivityManager(  944): Killing 6196:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6196,
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155
E/WifiStateMachine(  944): processMsg: ConnectedState
,E/WifiStateMachine(  944):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=1.4, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:2758] from screen [on:0 period:-958107242] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
,E/WifiStateMachine(  944):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=1.4, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-958107242] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  944):  get link layer stats 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -67 abnormalRssiCnt = 0 newLinkSpeed = 57
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-67 linkspeed=57
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-67 "NG700"WPA_PSK
,E/WifiStateMachine(  944): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.69 txretriesrate=0.00 rxrate=1.11 userTriggerdPenalty0
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  944):  good link -> stuck count =0
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  944):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  944):  isHighRSSI       ---> score=61
E/WifiStateMachine(  944): handleMessage: X
D/WifiWatchdogStateMachine(  944): RSSI current: 3 new: -67, 3,
,D/Process (  944): killProcessQuiet, pid=6220
I/ActivityManager(  944): Killing 6220:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6220,
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=241
,I/PMS     (  944): Going to sleep due to screen timeout (uid 1000)...,
,D/ActivityManager(  944): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{2f0aa894 #7 A=.Prism U=0 sz=1}
W/PMS     (  944): mWirelessDisplayManager is null
I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@258ce9d4
W/PMS     (  944): mWirelessDisplayManager is still null
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  944): pid=944, uid=1000
W/PMN     (  944): goingToSleep
W/SensorService(  944): Active sensors: size = 4
I/PMS     (  944): Sleeping (uid 1000)...
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
D/XAN-DPS (  944): prepareColorFade 1
,W/SensorService(  944): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@258ce9d4, eanble = 0, strlen(mName) = 91
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  944): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@4837950
W/SensorService(  944): Listener[1] = com.htc.smartdim.sensor_eye@49accc4
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  944): acquireWL(3d5f0f3d): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 944 1000 null
,W/PMN     (  944): goingToSleep done
I/FeedHostManager( 1577): [onPause]
I/FeedProviderManager( 1577): onPause
I/FeedHostManager( 1577): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@80e955f
I/SocialFeedProvider( 1577): +onPause
I/SocialFeedProvider( 1577): -onPause
,D/AlarmManager(  944): ACTION_SCREEN_ON
,W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/ActivityManager(  944): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6576 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/PMS     (  944): releaseWL(3d5f0f3d): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/AlarmManager(  944): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done recovering
I/AlarmManager(  944): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done EPS screen off alarm recovering
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  944): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  944): Build Date: 03/09/15 Mon
I/Adreno-EGL(  944): Local Branch: 
I/Adreno-EGL(  944): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  944): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  944):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  944): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  944):  packet count Tx=155 Rx=241
W/HtcLockScreen( 1220): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,E/WifiDataStallTracker(  944): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  944): updateDataStallInfo: mDataStallTxRxSum={txSum=138 rxSum=125} preTxRxSum={txSum=138 rxSum=125}
D/WifiDataStallTracker(  944): updateDataStallInfo: NONE
D/WifiDataStallTracker(  944): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  944): handleMessage: E msg.what=131167,
E/WifiStateMachine(  944): processMsg: ConnectedState
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: DriverStartedState
E/WifiStateMachine(  944):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1330): SET_SCREEN_ON:On
I/wpa_supplicant( 1330): htc_wext_set_keepalive +
I/wpa_supplicant( 1330): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1330): getPrivFuncNum +	
I/wpa_supplicant( 1330): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1330): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1330): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  944): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  944): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  944): handleScreenStateChanged Exit: true
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,V/SRS_Proc(  401): ParamSet string: screen_state=on,
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  944): handleMessage: E msg.what=155650
D/NetworkPolicy(  944): updateScreenOn: false
D/WifiController(  944): processMsg: DeviceActiveState
V/NetworkPolicy(  944): updateIfacesLocked()
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative RSSI = -67 abnormalRssiCnt = 0 newLinkSpeed = 57
E/WifiStateMachine(  944): fetchRssiLinkSpeedAndFrequencyNative rssi=-67 linkspeed=57
E/WifiConfigStore(  944): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-67 "NG700"WPA_PSK
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131127
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131129
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1330): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  944): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiStateMachine(  944): handleMessage: X
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST CLEAR 
,W/ResourcesManager( 6576): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/IntentController( 1220): receive(android.intent.action.SCREEN_ON,1,false)
,I/CalendarProvider2( 6576): Created com.android.providers.calendar.CalendarAlarmManager@33e32101(com.htc.providers.calendar.HtcCalendarProvider@13898ba6)
,D/PMS     (  944): acquireWL(3dfe04fb): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1837 10024 WorkSource{10024 com.google.android.gms}
D/CalendarProvider2( 6576): wait start:true,
D/PMS     (  944): acquireWL(309df5d7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1837 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3dfe04fb): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  944): prepareColorFade done
,D/XAN-DPS (  944): setBrightness to 0
,D/PMS     (  944): releaseWL(309df5d7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@4837950
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  944): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/SensorService(  944): pid=944, uid=1000
V/ActivityManager(  944): Display changed displayId=0
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@4837950, eanble = 0, strlen(mName) = 66
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@49accc4
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1339): [EventService]  onDisplayChanged: 0
E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL true Token 12 num clients 6
,D/CalendarProvider2( 6576): wait end:false,
D/DotMatrix( 1339): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/AlarmManager(  944): ACTION_SCREEN_OFF
,I/AlarmManager(  944): [AlarmQueuing] screen off now: 
,I/AlarmManager(  944): [AlarmQueuing] data connection: true
I/AlarmManager(  944): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  944): ENABLE_TRAFFIC_STATS_POLL false Token 12
,D/WifiDataStallTracker(  944): stopDataStallAlarm 
E/WifiDataStallTracker(  944): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  944): handleMessage: E msg.what=131167
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
,E/WifiStateMachine(  944):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: DriverStartedState
,E/WifiStateMachine(  944):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1330): SET_SCREEN_ON:Off
I/wpa_supplicant( 1330): htc_wext_set_keepalive +
D/NetworkPolicy(  944): updateScreenOn: false
V/SRS_Proc(  401): ParamSet string: screen_state=off
V/NetworkPolicy(  944): updateIfacesLocked()
I/wpa_supplicant( 1330): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/wpa_supplicant( 1330): getPrivFuncNum +	
I/wpa_supplicant( 1330): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1330): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1330): htc_wext_set_keepalive gateway addr = c0a80101
,E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
I/wpa_supplicant( 1330): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  944): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  944): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  944): handleScreenStateChanged Exit: false
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): handleMessage: X
D/WifiController(  944): handleMessage: E msg.what=155651
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6607 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/SensorManager( 1220): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@3e8bec27, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  944): pid=1220, uid=10041
W/SensorService(  944): Active sensors: size = 4
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
,W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@3e8bec27, eanble = 1, strlen(mName) = 57
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@49accc4
W/SensorService(  944): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@3e8bec27
,W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1339): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1534): start background delete task...
,I/IntentController( 1220): receive(android.intent.action.SCREEN_OFF,1,false)
,D/PMS     (  944): acquireWL(12e21873): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1837 10024 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1534): size: 0 , 0
,D/ContactMessageStore( 1534): Background delete complete
D/PMS     (  944): acquireWL(9a9a330): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1837 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(12e21873): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  944): releaseWL(9a9a330): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 6607): MY_DEBUG = false,
,W/ContextImpl( 6607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  944): Excessive delay in setPowerMode(): 291ms
,D/PMS     (  944): Setting HAL interactive mode to false
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  944): Setting HAL interactive mode to false done
D/PMS     (  944): Setting HAL auto-suspend mode to true
D/PMS     (  944): Setting HAL auto-suspend mode done
D/HABCtrl (  944): TPE algorithm. remove timeout.
I/InputMethodManagerService(  944): screenObserver, isScreenOn=false
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  944): Disable input method client, pid=1577
D/PMS     (  944): OOBE c monitor 11
I/InputManager(  944): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1220): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/SmartSyncUtils( 6607): isEpsOn(), nState = 0
,D/NfcService( 1550): ScreenObserver: OFF
I/RemoteViews( 1220): setHTCTheme(com.htc.updater,true,33751145)
D/NfcService( 1550): applyRouting - 0
,D/PMS     (  944): acquireWL(3e3bc8cf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): acquireWL(15bdc25c): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1550 1027 null
,D/NfcService( 1550): applyRouting -2
D/PMS     (  944): releaseWL(3e3bc8cf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NfcService( 1550): applyRouting
D/HtcPowerSaver(  944): updateBatteryInfo
D/NfcService( 1550): Ignore this applyRouting...
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): releaseWL(15bdc25c): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/RemoteViews( 1220): apply : com.htc.updater 1 11 1 36
,D/PMS     (  944): acquireWL(22bf965): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6607 1000 null
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,D/PowerUI ( 1220): closing low battery warning: level=100
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  944): Init customizeScreenOffDelayClass error
,D/PMS     (  944): releaseWL(22bf965): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6607): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6607): isEpsOn(), nState = 0
,I/ClockController( 1220): stop clock update:screen off,
I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 6607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@49accc4
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@49accc4, eanble = 0, strlen(mName) = 35
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3e8bec27
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 2
,W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@49accc4, eanble = 0, strlen(mName) = 35
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3e8bec27
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@49accc4
,I/ActivityManager(  944): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6640 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL false Token 3
E/ActivityThread(  944): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3e517ad that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3e517ad that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): ,	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  944): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  944): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
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
,E/ActivityThread(  944): ,	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/PowerUsageList:PowerUsageHelper( 6607): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6607): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  944): killProcessQuiet, pid=5985
I/ActivityManager(  944): Killing 5985:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6607): getMobilePolicyEnabled, result = true,
,E/WifiTrafficPoller(  944): ADD_CLIENT: 7,
D/WifiService(  944): New client listening to asynchronous messages
,I/ActivityManager(  944): Recipient 5985
,D/PowerUsageList:PowerUsageHelper( 6607): MY_DEBUG = false,
,D/Process (  944): killProcessQuiet, pid=6251
I/ActivityManager(  944): Killing 6251:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  944): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  944): Recipient 6251,
,I/CalendarProvider2( 6576): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,W/ContentResolver( 6576): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  944): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6664 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  944): killProcessQuiet, pid=5404
I/ActivityManager(  944): Killing 5404:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5404
,W/ResourcesManager( 6664): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6664): onCreate
,D/ProviderChangeReceiver( 6664): ---------------------------------------------------
,D/ProviderChangeReceiver( 6664): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  944): killProcessQuiet, pid=5462,
I/ActivityManager(  944): Killing 5462:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 6664): start to updateAlertNotification!
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155
E/WifiStateMachine(  944): processMsg: ConnectedState
,E/WifiStateMachine(  944):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-958104222] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-958104219] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): handleMessage: X
,D/PMS     (  944): releaseWL(2de92366): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  944): Recipient 5462
,D/HtcAlertService( 6664): No fired or scheduled alerts
,D/HtcAlertUtils( 6664): -- cancelReminderNotification --
,D/HtcAlertUtils( 6664): broadcastExistReminder!
,D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  944): handleMessage: E msg.what=131155
E/WifiStateMachine(  944): processMsg: ConnectedState
E/WifiStateMachine(  944):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1554] from screen [on:0 period:-958102664] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  944): processMsg: L2ConnectedState
E/WifiStateMachine(  944):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-67 f=2412 sc=60 link=57 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-958102662] gl hn u24 rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  944): handleMessage: X
,D/HtcUPManager( 1220): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  944): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1534): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1534): MSG_NOTIFY_CS_TO_SYNC <<,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Process (  944): killProcessQuiet, pid=5633,
I/ActivityManager(  944): Killing 5633:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5633
,D/PMS     (  944): acquireWL(192a848): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{3e4447bf: PendingIntentRecord{da8ee8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=125980, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{a67c6e1: PendingIntentRecord{3fce6c06 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144034, Int=0
,D/PMS     (  944): releaseWL(192a848): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/WeatherUtility( 1220): Weather sync is On
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  944): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  944): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  944): acquireWL(227202c7): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 944 1000 null
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8,
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  944): [NET] android_getaddrinfo_proxy+
D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  944): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  944): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  944): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  944): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  944): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  944): acquireWL(2020463): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 944 1000 null
D/GpsLocationProvider(  944):  [handleDownloadXtraData]inject done.
D/PMS     (  944): releaseWL(227202c7): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  944): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  944): releaseWL(2020463): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1534): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1534): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  944): acquireWL(3fc43860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(3fc43860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive-
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  944): updateBatteryInfo
D/WifiController(  944): handleMessage: E msg.what=155652
D/PMS     (  944): runPSCheck
D/WifiController(  944): processMsg: DeviceActiveState
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: StaEnabledState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DefaultState
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  944): handleMessage: X
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1534): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  944): acquireWL(29f97119): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{3200f5de: PendingIntentRecord{1d0683bf android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455035860813, Int=0
D/PMS     (  944): acquireWL(3ca47a8c): PARTIAL_WAKE_LOCK  *backup* 0x1 944 1000 null
V/AlarmManager(  944): sending alarm PendingIntent{3e4447bf: PendingIntentRecord{da8ee8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=185979, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{3a705d5: PendingIntentRecord{9a291ea android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=200937, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{27a99cdb: PendingIntentRecord{3d64b378 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190668, Int=0
,W/BackupManagerService(  944): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  944): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  944): releaseWL(3ca47a8c): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  944): acquireWL(195f2a51): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(180fe2b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1220): Weather sync is On
D/PMS     (  944): releaseWL(29f97119): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/PMS     (  944): releaseWL(195f2a51): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  944): releaseWL(180fe2b6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(26067990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(26067990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(3f2bd289): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3f2bd289): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): acquireWL(1ec4928e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(262ddaaf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(12f60e45): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(1ec4928e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1958): Vacuum at: now=1455035895199 tag=VacuumService,
,D/PMS     (  944): releaseWL(262ddaaf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(310772cb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1958): Using platform SSLCertificateSocketFactory
,D/PMS     (  944): releaseWL(310772cb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  944): acquireWL(3927eaa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3927eaa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1958): No account for auth token provided,
,D/libc    ( 1958): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1958): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1958): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1958): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1958): [NET] android_getaddrinfo_proxy+
D/libc    ( 1958): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1958): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1958): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1958): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1958): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1958): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1958): No account for auth token provided,
,W/Uploader( 1958): No account for auth token provided,
,W/Uploader( 1958):  no longer exists, so no auth token.,
,W/Uploader( 1958): No account for auth token provided,
,I/GLSUser ( 1958): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1958): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1958): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1958): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1958): Explicit concurrent mark sweep GC freed 23695(1323KB) AllocSpace objects, 5(420KB) LOS objects, 48% free, 4MB/8MB, paused 980us total 93.067ms
,I/art     (  944): Explicit concurrent mark sweep GC freed 35886(1959KB) AllocSpace objects, 4(1080KB) LOS objects, 33% free, 18MB/28MB, paused 1.705ms total 164.002ms,
,D/DotMatrix( 1339): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1339): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1220): reapply : com.google.android.gms 3 40
E/Uploader( 1958): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1958): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1958): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1958): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1958): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1958): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1958): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1958): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1958): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1958): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1958): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1958): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1958): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1958): No account for auth token provided,
,D/PMS     (  944): releaseWL(12f60e45): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(3b1012b5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3b1012b5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  944): acquireWL(38894d4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(38894d4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1638): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@218e07c0
,D/Process (  944): killProcessQuiet, pid=6431
I/ActivityManager(  944): Killing 6431:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6431
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 1
,D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): acquireWL(393ea4bb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): releaseWL(393ea4bb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
,D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  944): updateBatteryInfo
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: DeviceActiveState
,I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: StaEnabledState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  944): acquireWL(197f4dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(197f4dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
,D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState,
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1330): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  944): acquireWL(31fc2531): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{3e4447bf: PendingIntentRecord{da8ee8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=245980, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{2da8d197: PendingIntentRecord{12876f84 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1455036035523, Int=0
,D/PMS     (  944): releaseWL(31fc2531): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,I/art     ( 1577): Background sticky concurrent mark sweep GC freed 67008(4MB) AllocSpace objects, 4(400KB) LOS objects, 12% free, 32MB/37MB, paused 15.412ms total 73.988ms,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  944): acquireWL(2bbce36d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null,
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(2bbce36d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
,D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1),
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1958): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1958): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1958): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1958): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1339): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1339): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/GLSActivity( 1958): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1958): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1958): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1958): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1958): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1958): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1958): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5944): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5944): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1220): reapply : com.google.android.gms 4 40
,W/System  ( 5944): Ignoring header User-Agent because its value was null.
,D/libc    ( 5944): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5944): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5944): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5944): [NET] android_getaddrinfo_proxy+
D/libc    ( 5944): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5944): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 5
,D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PMS     (  944): acquireWL(38cb4e87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  944): n_update end
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  944): releaseWL(38cb4e87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
,D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DefaultState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): handleMessage: X
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  944): << updateStatus
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  944): acquireWL(23e7c1b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): releaseWL(23e7c1b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): runPSCheck
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  944): >> updateStatus
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1534): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1534): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1534): sku_id=118
D/ContactMessageStore( 1534): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1534): start background delete task...
,D/ContactMessageStore( 1534): size: 0 , 0
,D/ContactMessageStore( 1534): Background delete complete
,D/PMS     (  944): acquireWL(2bea81dd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0,
I/BatteryService(  944): n_update end
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): releaseWL(2bea81dd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  944): >> updateStatus
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: E msg.what=155652
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  944): acquireWL(3458d152): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null,
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(3458d152): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DefaultState
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  944): handleMessage: X
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
,D/PMS     (  944): acquireWL(11044c23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/UsbnetService(  944): onReceive BATTERY_CHANGED
I/BatteryService(  944): n_update end
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  944): releaseWL(11044c23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/NotificationService(  944): plugged=true pluggin=true
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  944): processMsg: StaEnabledState
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: DefaultState
D/HtcPowerSaver(  944): updateBatteryInfo
D/WifiController(  944): handleMessage: X
D/PMS     (  944): runPSCheck
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): >> updateStatus
,D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  944): acquireWL(14194520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(14194520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): runPSCheck,
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  944): Checking...
,D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
,D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  944): acquireWL(18925ed9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000},
I/bt-btm  ( 3102): Received oneshot timer event complete
V/AlarmManager(  944): sending alarm PendingIntent{3e4447bf: PendingIntentRecord{da8ee8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=365980, Int=0
I/bt-btm  ( 3102): btm_ble_timeout
V/AlarmManager(  944): sending alarm PendingIntent{40eb09e: PendingIntentRecord{2c45877f com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941310, Int=0
I/bt-btm  ( 3102): btm_gen_resolvable_private_addr
D/PMS     (  944): acquireWL(141d934c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3102 1002 null
,D/bt-btm  ( 3102): btm_ble_rand_enc_complete,
I/bt-btm  ( 3102): btm_gen_resolve_paddr_low
D/PMS     (  944): releaseWL(18925ed9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/bt-smp  ( 3102): smp_encrypt_data
W/bt-smp  ( 3102): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3102): Plain text(LSB ~ MSB) = 4c 01 62 00 00 00 00 00 00 00 00 00 00 00 00 00 ,
W/bt-smp  ( 3102): Encrypted text(LSB ~ MSB) = 47 92 9d 38 5a 14 55 ff ab 11 26 5b f4 0e be 1d 
I/bt-btm  ( 3102): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3102): Stopping oneshot timer
D/bt-btm  ( 3102): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1220): Weather sync is On,
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/PMS     (  944): releaseWL(141d934c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  944): acquireWL(c410f95): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null,
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/BatteryService(  944): n_update end
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): releaseWL(c410f95): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/NotificationService(  944): plugged=true pluggin=true
D/WifiController(  944): handleMessage: E msg.what=155652
D/PMS     (  944): runPSCheck
D/WifiController(  944): processMsg: DeviceActiveState
D/HtcPowerSaver(  944): Checking...
,D/WifiController(  944): processMsg: StaEnabledState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: X
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  944): << updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  944): acquireWL(2cb138aa): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{17df4322: PendingIntentRecord{3ed021b3 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805408, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{3e4447bf: PendingIntentRecord{da8ee8c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=965979, Int=0
,D/Finsky  ( 5944): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  944): sending alarm PendingIntent{34369838: PendingIntentRecord{38f44af9 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455036377183, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{10f01011: PendingIntentRecord{19423576 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=937459, Int=0
,I/ActivityManager(  944): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6703 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  944): sending alarm PendingIntent{4d8ffe4: PendingIntentRecord{3cb49c4d com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1455036545394, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{11143302: PendingIntentRecord{6d06f11 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455036661579, Int=0
D/PMS     (  944): acquireWL(c167d4e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(c167d4e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  944): releaseWL(2cb138aa): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
D/PowerUsageList:PowerUsageHelper( 6607): MY_DEBUG = false
,D/PowerUsageService( 6607): repeat time = 1455037561652
,I/GLSUser ( 1958): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1958): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1958): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1958): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5944): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1958): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1958): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1958): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1958): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 6607): PowerProfile::POWER_SCREEN_FULL = 154.8
,E/cutils-trace( 6725): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6725): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6725): dex2oat: override thread count:4
,I/GLSUser ( 1958): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1958): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1958): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1958): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerUsageList:BatterySipperExt( 6607): gen(), null == sipper.uidObj, userId = 0
,W/Finsky  ( 5944): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/GCM     ( 1958): Message class com.google.f.a.a.i,
D/PMS     (  944): acquireWL(1b4ebaae): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1958 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(1b4ebaae): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1958): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1958): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1958): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1958): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1958): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5944): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
D/Finsky  ( 5944): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5944): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5944): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1837): client connected with version: 7571000,
,I/dex2oat ( 6725): dex2oat took 703.078ms (threads: 4),
,I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): VersionName:             1.2.853019,
,I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): VersionCode:             148001224,
I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6703): ApplicationMonitor {16055b00}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6703): PnsModel {1a1d8d83}: update(): Update registration caused by: alarm
,I/PushClient( 6703): PnsConfigModel {15222a56}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6703): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6703): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6703): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6703): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  944): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6735 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6735): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6735 dbg=false s=true
,I/DeviceManagement( 6735): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6735): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6735): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6735): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6735): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@38b2bc32] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6735): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6735): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6735): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6735): SessionStateController: Checking invariants...
,I/DeviceManagement( 6735): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6735): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6735): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6735): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@38b2bc32],
,I/DeviceManagement( 6735): WorkflowService: Stopping workflow service
,D/Process (  944): killProcessQuiet, pid=6361,
I/ActivityManager(  944): Killing 6361:com.test.thalitest/u0a366 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6703): PnsModel {1a1d8d83}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  944): Recipient 6361,
E/InputEventReceiver( 1383): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{8015548 uid 10366 pid 6361} (c)'
,D/Process (  944): killProcessQuiet, pid=6312
,I/ActivityManager(  944): Killing 6312:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 6312
,D/PMS     (  944): acquireWL(3e654836): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10072},
V/AlarmManager(  944): sending alarm PendingIntent{3ce46337: PendingIntentRecord{3721260f com.android.vending startService}}, i=null, t=0, cnt=1, w=1455036676874, Int=0
D/PMS     (  944): releaseWL(3e654836): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5944): [602] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5944): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  944): acquireWL(370330a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{2805de0d: PendingIntentRecord{1f35b1c2 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455036708161, Int=0
,D/SmartSyncUtils( 6607): isEpsOn(), nState = 0
,D/PMS     (  944): releaseWL(370330a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  944): acquireWL(2411fbd3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6607 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 6607): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6607): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6607): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6607): SettingOnTime = 1455084000000, randomSettingOnTime = 1455083687000,
D/SmartSyncScreenOnOffTimeReceiver( 6607): SettingOffTime = 1455062400000, randomSettingOffTime = 1455069210000
,D/SmartSyncScreenOnOffTimeReceiver( 6607): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6607): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6607): bNightModeTurnOffOnce = false
,D/PMS     (  944): releaseWL(2411fbd3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  944): acquireWL(2e94b310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/BatteryService(  944): n_update end
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  944): battery changed pluggedType: 2
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  944): handleMessage: X
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/PMS     (  944): releaseWL(2e94b310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  944): acquireWL(323f4e09): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(323f4e09): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1220): closing low battery warning: level=100,
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): runPSCheck
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  944): acquireWL(12b1280e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(12b1280e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  944): updateBatteryInfo,
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): >> updateStatus
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  944): battery changed pluggedType: 2
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
,D/WifiController(  944): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  944): User[0] Flushing usage stats to disk
,D/PMS     (  944): acquireWL(3876822f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(3876822f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): Checking...
,D/DotMatrix( 1339): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): >> updateStatus
D/DotMatrix( 1339): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,D/UsbnetService(  944): BroadcastReceiver::onReceive+,
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): << updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/NotificationService(  944): plugged=true pluggin=true
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms)
```
