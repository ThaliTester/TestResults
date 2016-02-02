#### Test 57924002d5e0b14_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiStateMachine(  967): handleMessage: E msg.what=131155
E/WifiStateMachine(  967): processMsg: ConnectedState
I/HtcModeClient( 3153): handler message = 4011
E/HtcModeClient( 3153): Check connection and retry 12 times.
E/WifiStateMachine(  967):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:2010] from screen [on:0 period:-1553213303] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1553213302] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  967):  get link layer stats 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SIGNAL_POLL'
E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 11 num clients 6
--------- beginning of system
D/WIFI_ICON( 1221): WifiActivity: 2
E/WifiTrafficPoller(  967):  packet count Tx=139 Rx=230
E/WifiTrafficPoller(  967): notifying of data activity 2
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
I/wpa_supplicant( 1334): environment dirty rate=0 [0][0][0]
D/wpa_supplicant( 1334): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1334): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1334): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1334): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1334): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1334): wlan0: Scan completed in 2.158717 seconds
D/wpa_supplicant( 1334): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1334): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1334): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
I/wpa_supplicant( 1334): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
I/wpa_supplicant( 1334): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1334): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/wpa_supplicant( 1334): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
D/wpa_supplicant( 1334): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1334): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1334): wlan0: Scan-only results received
D/wpa_supplicant( 1334): wlan0: Radio work 'scan'@0x55b287d680 done in 2.159711 seconds
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  967): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  967): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.60 txretriesrate=0.00 rxrate=1.16 userTriggerdPenalty0
E/WifiStateMachine(  967):  good link -> stuck count =0
E/WifiStateMachine(  967):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  967):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147461
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1334): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  967): [1,454,440,700,199 ms] noteScanEnd no scan source
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1334): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  967): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@1c46861e sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  967): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  967): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  967): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  967): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  967):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  967): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  967): 01ABC c2:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  967): ageScanResultsOut delay 40000 size 4 now 1454440700202
E/WifiAutoJoinController (  967): newSupplicantResults size=4 known=1 true
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1334): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  967): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  967): ssid=NG700
E/WifiAutoJoinController (  967): id=0
E/WifiAutoJoinController (  967): mode=station
E/WifiAutoJoinController (  967): pairwise_cipher=CCMP
E/WifiAutoJoinController (  967): group_cipher=CCMP
E/WifiAutoJoinController (  967): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  967): wpa_state=COMPLETED
E/WifiAutoJoinController (  967): ip_address=192.168.1.130
E/WifiAutoJoinController (  967): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  967): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  967): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  967): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  967): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-58,-127) num=(1,0)
E/WifiAutoJoinController (  967): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  967): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-58 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  967): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  967): Done attemptAutoJoin status=0
E/WifiConfigStore(  967):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  967): handleMessage: X
D/WifiManager( 1832): getScanResults: Base Package Name=com.google.android.gms, uid=10024
D/libc    ( 4419): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4419): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4419): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4419): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4419): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4419): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4419): Sending checkin request (8409 bytes)
I/CheckinRequestBuilder( 4419): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  967): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4419): Failed to find provider info for com.google.android.wearable.settings
I/GLSUser ( 1920): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1920): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1920): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1920): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1920): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 4419): awaiting user notification for token
I/CheckinRequestBuilder( 4419): Classify the device as Phone.
I/CheckinTask( 4419): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4419): Checking schedule, now: 1454440700895 next: 1454977532889
I/CheckinService( 4419): active receiver: disabled
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4419, uid=10024, userID:0
D/PMS     (  967): releaseWL(3a711292): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6374 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/PhoneMonitor( 6374): Register our PhoneStateListener
V/SetupWizard( 6374): Connected to Gservices successfully
D/ChimeraCfgMgr( 4419): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PhoneMonitor( 6374): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/ChimeraCfgMgr( 4419): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PhoneMonitor( 6374): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1920): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/GLSUser ( 1920): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1920): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1920): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1920): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1920): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Kids    ( 4419): [AccountUtils] Account not ready
W/Kids    ( 4419): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4419): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4419): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4419): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4419): 	at java.lang.Thread.run(Thread.java:818)
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  967):  packet count Tx=155 Rx=244
E/WifiTrafficPoller(  967): notifying of data activity 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/cutils-trace( 6400): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6400): ====startRecUseTime====
D/htc.customization.log.level( 6400):  is 
W/CustomizationLogLevel( 6400): Level value is invalid, use default level 2
D/CustomizationManager( 6400):  Read ACC file spent 0.044 (s)
D/CIDMapFileReader( 6400): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6400): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6400): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6400): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6400): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6400): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6400): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6400): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6400): Parsing tag category name = system
I/CustomizationCIDLoader( 6400): Parsing tag category name = application
I/CustomizationCIDLoader( 6400): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6400): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6400): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6400): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6400): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6400): add string-array item, value = 42507
I/CustomizationCIDLoader( 6400): add string-array item, value = 21902
I/CustomizationCIDLoader( 6400): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6400): add string-array item, value = 23420
I/CustomizationCIDLoader( 6400): add string-array item, value = 22299
I/CustomizationCIDLoader( 6400): add string-array item, value = 24002
I/CustomizationCIDLoader( 6400): add string-array item, value = 23210
I/CustomizationCIDLoader( 6400): add string-array item, value = 23205
I/CustomizationCIDLoader( 6400): add string-array item, value = 23806
I/CustomizationCIDLoader( 6400): add string-array item, value = 23430
I/CustomizationCIDLoader( 6400): add string-array item, value = 23408
I/CustomizationCIDLoader( 6400): add string-array item, value = 27205
I/CustomizationCIDLoader( 6400): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6400): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6400):  Read CID file spent 0.091 (s)
D/CustomizationManager( 6400):  All configurations done spent 0.091 (s)
E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  967):  packet count Tx=155 Rx=244
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  967): notifying of data activity 0
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6400 on display 0
D/PMS     (  967): acquireHCC(1e5e0ba2): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 967 1000 null
D/PMS     (  967): acquireHCC(36e28033): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 967 1000 null
W/asset   (  967): Copying FileAsset 0x55a8e7a6e0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  967): acquireWL(24353fee): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 967 1000 null
I/FeedHostManager( 1544): [onPause]
I/AnimationUtil(  967): isHTCRecent(ThaliTest/Recent screens.)/6
I/FeedProviderManager( 1544): onPause
I/FeedHostManager( 1544): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@c2e1321
I/SocialFeedProvider( 1544): +onPause
I/SocialFeedProvider( 1544): -onPause
W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6418 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  967): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  967): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  967): hiding MENU key
W/asset   ( 6418): Copying FileAsset 0xac94dd18 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1544): [trimMemory] 20
,I/WebViewFactory( 6418): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6418): Time to load native libraries: 10 ms (timestamps 1167-1177),
,I/LibraryLoader( 6418): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6418): Binding Chromium to main looper Looper (main, tid 1) {3eb395dd},
I/LibraryLoader( 6418): Expected native library version number "",actual native library version number ""
,I/chromium( 6418): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6418): Initializing chromium process, singleProcess=true,
,W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6418): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6418): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6418): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6418): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6418): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6418): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6418): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6418): Local Branch: 
I/Adreno-EGL( 6418): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6418): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6418):                  d74aa161a12b9c6fc6332151
,W/System.err(  967): java.lang.Throwable: stack dump,
W/System.err(  967): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  967): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  967): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25f6177f:true
,D/BluetoothAdapter( 6418): 530085022: getState(). Returning 12
,W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6418): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6418): CordovaWebView is running on device made by: HTC
,W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring,
,W/chromium( 6418): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 6418): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6418): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@f99414e, mServedView=org.apache.cordova.engine.SystemWebView{267ac26f VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1a5ccb7c
,I/InputMethodManagerService(  967): Disable input method client, pid=1544
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  967): Enable input method client, pid=6418,
,I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +805ms
,D/PMS     (  967): releaseWL(24353fee): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,W/BindingManager( 6418): Cannot call determinedVisibility() - never saw a connection for the pid: 6418
,W/XT9_C   ( 1392): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/XT9_C   ( 1392): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1392): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1392): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 11 num clients 6,
,E/WifiTrafficPoller(  967):  packet count Tx=155 Rx=244
,D/JsMessageQueue( 6418): Set native->JS mode to OnlineEventsBridgeMode
,E/WifiStateMachine(  967): handleMessage: E msg.what=131155
,E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553210148] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
,E/WifiStateMachine(  967):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553210145] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  967):  get link layer stats 0
,W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1334): environment dirty rate=0 [17][0][0]
,E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
,E/WifiStateMachine(  967): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.30 txretriesrate=0.00 rxrate=7.58 userTriggerdPenalty0
E/WifiStateMachine(  967):  good link -> stuck count =0
E/WifiStateMachine(  967):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  967):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  967): handleMessage: X
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/jxcore_app_log( 6418): JniHelper::setJavaVM(0xab7e08f8), pthread_self() = -1398533344
,I/chromium( 6418): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  967):  packet count Tx=155 Rx=245
E/WifiTrafficPoller(  967): notifying of data activity 1
D/WIFI_ICON( 1221): WifiActivity: 1
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  967): releaseHCC(1e5e0ba2): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  967): releaseHCC(36e28033): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6418): Initializing JXcore engine,
W/jxcore-log( 6418): JXcore engine is ready,
,W/jxcore-log( 6418): Starting JXcore engine
,W/jxcore-log( 6418): Platform android,
W/jxcore-log( 6418): 
W/jxcore-log( 6418): Process ARCH arm
W/jxcore-log( 6418): 
,I/ActivityManager(  967): Killing 5830:com.google.android.gm/u0a106 (adj 15): empty #17,
D/Process (  967): killProcessQuiet, pid=5830
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5830
,D/Process (  967): killProcessQuiet, pid=5873
,I/ActivityManager(  967): Killing 5873:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/jxcore-log( 6418): JXcore Cordova bridge is ready!,
I/jxcore-log( 6418): 
W/jxcore-log( 6418): JXcore engine is started
,E/WifiDataStallTracker(  967): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  967): updateDataStallInfo: mDataStallTxRxSum={txSum=136 rxSum=122} preTxRxSum={txSum=120 rxSum=109}
D/WifiDataStallTracker(  967): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  967): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/ActivityManager(  967): Recipient 5873
,I/jxcore-log( 6418): Toggling radios to true,
I/jxcore-log( 6418): 
,D/BluetoothAdapter( 6418): enable(): BT is already enabled..!,
,D/WifiService(  967): New client listening to asynchronous messages,
E/WifiTrafficPoller(  967): ADD_CLIENT: 7
D/WifiManager( 6418): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  967): setWifiEnabled: true pid=6418, uid=10366
W/Settings:Agent(  967): MONITOR_LOG
W/Settings:Agent(  967): name: wifi_on
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  967): value: 2
I/WifiService(  967): isSprintWifiRestricted(): false
W/Settings:Agent(  967): >> traceCallingStack()
,I/WifiService(  967): isMdmWifiRestricted(): false
W/Settings:Agent(  967): Process.myPid(): 967
W/Settings:Agent(  967): Process.myTid(): 2036
W/Settings:Agent(  967): Process.myUid(): 1000
W/Settings:Agent(  967): 
W/Settings:Agent(  967): 
,W/System.err(  967): java.lang.Throwable: stack dump,
,W/System.err(  967): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  967): ,	,at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  967): 	,at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  967): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  967): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  967): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  967): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  967): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  967): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  967): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  967): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  967): 
W/Settings:Agent(  967): << traceCallingStack(): 21(ms)
D/WifiController(  967): handleMessage: E msg.what=155656
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): handleMessage: X
D/WifiManager( 6418): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  967): handleMessage: E msg.what=131145
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1334): wlan0: Cancelling scan request
D/wpa_supplicant( 1334): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1334): TDLS: Tear down peers
D/wpa_supplicant( 1334): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiManager( 6418): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 6418): Radios toggled
I/jxcore-log( 6418): 
I/jxcore-log( 6418): My device name is: HTC-HTC One M8s
I/jxcore-log( 6418): 
,D/wpa_supplicant( 1334): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1334): wlan0: Deauthentication notification
D/wpa_supplicant( 1334): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1334): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1334): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1334): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1334): enter disconnect check
I/wpa_supplicant( 1334): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1334): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1334): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  967): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  967): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/PMS     (  967): acquireWL(14f92c67): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  967): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  967): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 1334): TDLS: Remove peers on disassociation
D/UsbDeviceManager(  967): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1334): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1334): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1334): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1334): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55b287af88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1334):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1334): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1334): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1334): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1334): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1334): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1334): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1334): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1334): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1334): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1334): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1334): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1334): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1334): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1334): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1334): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1334): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1334): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1334): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1334): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: ConnectedState
E/WifiStateMachine(  967): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  967): release()
E/WifiStateMachine(  967): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  967): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/Tethering(  967): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
E/WifiMonitor(  967): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbnetService(  967): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,E/WifiStateMachine(  967): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  967): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  967): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1334): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1334): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1334): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1334): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1334): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1334): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1334): Power_Mode_Type mode = 0
I/wpa_supplicant( 1334): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1334): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  967): setDhcpActive: false
,V/NativeCrypto( 1920): Read error: ssl=0x55a8b42330: I/O error during system call, Connection timed out
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/PMS     (  967): acquireWL(18497a14): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  967): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/HtcModeClient( 3153): handler message = 4011
E/WifiStateMachine(  967): NetworkAgent != null
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  967):  packet count Tx=155 Rx=245
E/WifiTrafficPoller(  967): notifying of data activity 0
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WIFI_ICON( 1221): WifiActivity: 0,
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  967): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiDataStallTracker(  967): stopDataStallAlarm 
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
,D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL false Token 1
,I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/wpa_supplicant( 1334): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1334): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1334): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
V/NativeCrypto( 1920): SSL shutdown failed: ssl=0x55a8b42330: I/O error during system call, Broken pipe
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SAVE_CONFIG'
,D/wpa_supplicant( 1334): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1334): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1334): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  967):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  967): Start Disconnecting Watchdog 1
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131146
E/WifiStateMachine(  967): processMsg: DisconnectingState
E/WifiStateMachine(  967):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
,D/wpa_supplicant( 1334): wlan0: Control interface command 'RECONNECT'
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1334): wlan0: Selecting BSS from priority group 605
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1334): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1334): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/wpa_supplicant( 1334): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1334): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
D/wpa_supplicant( 1334): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1334): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1334): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1334):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1334): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1334): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x55b287cc00  current_ssid=0x0
D/wpa_supplicant( 1334): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1334): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1334): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1334): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1334): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1334): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
E/HtcModeClient( 3153): Check connection and retry 12 times. Stop service and kill this process.
D/wpa_supplicant( 1334): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1334): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1334): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1334): wlan0: Add radio work 'connect'@0x55b287d680
D/wpa_supplicant( 1334): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1334): wlan0: Starting radio work 'connect'@0x55b287d680 after 0.000175 second wait
I/wpa_supplicant( 1334): check if in concurrent case
I/wpa_supplicant( 1334): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147460
E/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiMonitor(  967): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=34 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  967):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=103795
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=103796
E/WifiStateMachine(  967): ConnectModeState: Network connection lost 
E/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  967): DisconnectedState call setCountryCode()
E/WifiStateMachine(  967):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/HtcMod,eClient( 3153): Don't start project servcice
D/wpa_supplicant( 1334): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1334): wlan0: Cancelling scan request
D/wpa_supplicant( 1334): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1334): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1334): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1334): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1334): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1334): RSN: PMKSA cache search - network_ctx=0x55b287cc00 try_opportunistic=0
D/wpa_supplicant( 1334): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1334): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1334): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1334): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1334): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1334): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1334): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1334): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1334): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1334): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1334): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1334): wlan0: State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1334): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1334): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1334): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1334): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1334): nl80211: Unsubscribe mgmt frames handle 0x888888dd3a0f4989 (mode change)
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1334): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b287c100
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=0104
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=040a
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=040b
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=040c
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=040d
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=090a
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=090b
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=090c
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=090d
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=0409506f9a09
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=7f506f9a09
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=0801
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=040e
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=06
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=0a07
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=0a11
D/wpa_supplicant( 1334): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b287c100 match=0a1a
D/wpa_supplicant( 1334): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1334):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334):   * freq=2412
D/wpa_supplicant( 1334):   * freq_hint=2412
D/wpa_supplicant( 1334):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1334):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1334):   * WPA Versions 0x2
D/wpa_supplicant( 1334):   * pairwise=0xfac04
D/wpa_supplicant( 1334):   * group=0xfac04
D/wpa_supplicant( 1334):   * akm=0xfac02
D/wpa_supplicant( 1334):   * Auth Type 0
D/wpa_supplicant( 1334): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55b287cc3a
D/wpa_supplicant( 1334): nl80211: Connect request send successfully
D/wpa_supplicant( 1334): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1334): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1334): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1334): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1334): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1334): Ongoing scan action - reject new request
E/WifiStateMachine(  967): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
D/HtcModeClient( 3153): setEject: MEDIA_EJECT_STATE = true
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131101
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/HtcModeClient( 3153): connectState: CONNECTION_READY = false
D/SilentMusic( 3153): call stop
D/HtcModeClient( 3153): close connection
E/WifiStateMachine(  967):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
W/HtcModeClient( 3153): leaveProjectMode: It does not enter ProjectMode
E/WifiStateMachine(  967):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
W/CANMesgAgentLocalSocket( 3153): read the terminate packet, so break
E/WifiStateMachine(  967):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  967): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=103804  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=103805  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  967): handleMessage: X
D/WifiNetworkAgent(  967): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131213
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState !CMD_TARGET_BSSID 34 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103809
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_TARGET_BSSID 34 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103809
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !CMD_TARGET_BSSID 34 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103810
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState !CMD_TARGET_BSSID 34 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103810
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=103811  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/TetherSettings( 5962): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5962): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5962): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5962): Cust_ConnectToPC   : spcsc>false
D/        ( 5962): Cust_ConnectToPC   : IPT>true
D/        ( 5962): Cust_ConnectToPC   : Singel_USB>false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=103816  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/ConnectivityService(  967): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  967): handleMessage: X
E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL false Token 16 num clients 7
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  967): releaseWL(18497a14): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
W/Settings( 5962): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMS     (  967): releaseWL(14f92c67): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/SmartNS_Utility( 5962): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5962): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
D/SmartNS_NSReceiver( 5962): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
V/NetworkPolicy(  967): updateNotificationsLocked()
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
W/ContextImpl( 5962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5962): setISNotification
D/SmartNS_Utility( 5962): usb_cable_connect = 1
D/SmartNS_Utility( 5962): usb_denied = 0
I/SmartNS_PSService( 5962): usb notificaiton:true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
I/ActionCombine( 5962): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:24
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/SmartNS_Utility( 5962): usb_cable_connect = 1
D/SmartNS_Utility( 5962): usb_denied = 0
I/SmartNS_PSService( 5962): usb notificaiton:true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5962): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
,D/WISPrService( 5962): >>>>>WISPrService start isConnected = true<<<<<
,D/wpa_supplicant( 1334): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1334): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1334): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1334): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1334): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1334): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1334): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1334): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1334): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/Tethering(  967): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1334): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1334): nl80211: Connect event
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1334): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1334): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1334): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1334): wlan0: Association info event
D/wpa_supplicant( 1334): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1334): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1334): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1334): wlan0: freq=2412 MHz
D/wpa_supplicant( 1334): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1334): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1334): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1334): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1334): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1334): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1334): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1334): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1334): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1334): wlan0: WPA: Clear old PTK
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1334): TDLS: Remove peers on association
D/wpa_supplicant( 1334): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1334): EAPOL: External notification - portValid=0
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1334): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1334): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1334): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1334): EAPOL: enable timer tick
D/Tethering(  967): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1334): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1334): wlan0: Setting authentication timeout: 10 sec 0 usec
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1334): wlan0: Cancelling scan request
I/wpa_supplicant( 1334): htc_wext_set_keepalive +
I/wpa_supplicant( 1334): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1334): getPrivFuncNum +	
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  967): WifiMonitor:,handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1334): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1334): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1334): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1334): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1334): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1334): wlan0:   EAPOL-Key type=2
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1334): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
,D/wpa_supplicant( 1334): wlan0:   key_length=16 key_data_length=0
,D/wpa_supplicant( 1334):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/ConnectivityService(  967): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/wpa_supplicant( 1334):   key_nonce - hexdump(len=32): 75 a4 bb a1 bd 00 47 17 bd 7d eb a7 22 77 70 9b 82 6a 80 b6 ba a0 ba 9e fc 4c ce fd c7 03 2a 76
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1334):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1334):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/ConnectivityService(  967): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/wpa_supplicant( 1334):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/Nat464Xlat(  967): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/wpa_supplicant( 1334):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1334): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1334): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1334): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=37 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  967): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  967): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  967): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  967): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  967):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=103905  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  967): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  967): setDetailed state send new extra info0x
D/HTCRequest(  967): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  967): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/UsbDeviceManager(  967): [USBNET] bCheckSuppFunc: cdc_network
D/WifiMonitor(  967): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/PMS     (  967): acquireWL(3f31f7ac): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
D/WifiMonitor(  967): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  967): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1334): WPA: Renewed SNonce - hexdump(len=32): 1f c4 3b 4c 24 e4 a4 0d 9e 1a be 58 94 d1 73 c9 3c f7 1e 70 b8 78 be 06 ac 66 3c ad 0b e6 62 37
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=,NG700]
D/wpa_supplicant( 1334): WPA: Nonce1 - hexdump(len=32): 1f c4 3b 4c 24 e4 a4 0d 9e 1a be 58 94 d1 73 c9 3c f7 1e 70 b8 78 be 06 ac 66 3c ad 0b e6 62 37
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1334): WPA: Nonce2 - hexdump(len=32): 75 a4 bb a1 bd 00 47 17 bd 7d eb a7 22 77 70 9b 82 6a 80 b6 ba a0 ba 9e fc 4c ce fd c7 03 2a 76
D/wpa_supplicant( 1334): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1334): WPA: PTK - hexdump(len=48): [REMOVED]
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1334): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1334): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1334): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1334): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1334): WPA: Derived Key MIC - hexdump(len=16): 4d 51 0c a9 23 f0 0a 6b 39 13 ea a6 dc f7 54 18
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  967): interfaceLinkStateChanged wlan0, true
D/Tethering(  967): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  967): TetherInterfaceSM: wlan0: enter InitialState
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  967):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=103911  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/wpa_supplicant( 1334): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1334): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1334): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1334): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1334):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1334):   key_nonce - hexdump(len=32): 75 a4 bb a1 bd 00 47 17 bd 7d eb a7 22 77 70 9b 82 6a 80 b6 ba a0 ba 9e fc 4c ce fd c7 03 2a 76
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1334):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1334):   key_rsc - hexdump(len=8): d6 61 00 00 00 00 00 00
D/wpa_supplicant( 1334):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/ConnectivityService(  967): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  967): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/wpa_supplicant( 1334):   key_mic - hexdump(len=16): ae 49 1e eb 47 f4 2e fc 3e 10 3b b0 b9 8d b1 af
D/wpa_supplicant( 1334): RSN: encrypted key data - hexdump(len=56): 63 2c 63 3c 30 50 90 f0 cf dc 6a 18 4e 67 30 79 e2 16 ec 37 f7 66 aa 52 ac 06 55 f1 bf 23 f1 90 ...
D,/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Disconnected - quitting
E/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 1334): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1334): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1334): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
E/WifiStateMachine(  967): handleMessage: E msg.what=147500
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/wpa_supplicant( 1334): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 cb bd ...
D/wpa_supplicant( 1334): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/NetworkManagementService(  967): Removing idletimer
D/wpa_supplicant( 1334): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1334): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1334): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1334): WPA: Derived Key MIC - hexdump(len=16): db 8a f9 46 5c 52 5a f8 01 49 1e f8 77 4b 97 0b
D/wpa_supplicant( 1334): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1334): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55b287d390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1334): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1334): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1334):    addr=c0:ff:d4:d3:aa:48
E/WifiStateMachine(  967):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
E/WifiStateMachine(  967):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  967): Enter handleAssociatedWithEvent
D/WifiStateMachine(  967): Associated
D/wpa_supplicant( 1334): EAPOL: External notification - portValid=1
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1334): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1334): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1334): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1334): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1334): WPA: RSC - hexdump(len=6): d6 61 00 00 00 00
D/wpa_supplicant( 1334): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5586c1ae68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/WifiStateMachine(  967): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/WifiStateMachine(  967): Exit handleAssociatedWithEvent
D/wpa_supplicant( 1334): nl80211: KEY_SEQ - hexdump(len=6): d6 61 00 00 00 00
I/SecurityController( 1221): onLost 100
D/wpa_supplicant( 1334):    broadcast key
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/WifiStateMachine(  967):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=103914  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1334): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1334): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1334): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 1334): wlan0: Radio work 'connect'@0x55b287d680 done in 0.120342 seconds
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=40 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1334): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1334): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  967): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=41 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  967): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1334): wlan0: Connect to SSID: NG700
D/WifiService(  967): New client listening to asynchronous messages
D/wpa_supplicant( 1334): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1334): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  967): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=43 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  967): couldn't identify event type - Connect to SSID: NG700
E/WifiStateMachine(  967): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 1334): set send_ind_to_ndc = 0
I/wpa_supplicant( 1334): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1334): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1334): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1334): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1334): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1334): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1334): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1334): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1334): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1334): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1334): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1334): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1334): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/Tethering(  967): interfaceLinkStateChanged wlan0, true
D/Tethering(  967): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1334): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  967): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  967): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor(  967): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbnetService(  967): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 17
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/usbnet  (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiTrafficPoller(  967): ADD_CLIENT: 8
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=103926  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  967): handleMessage: X
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: DisconnectedState
E/WifiStateMachine(  967):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=103935  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  967): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/PMS     (  967): releaseWL(3f31f7ac): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=103935  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147459
E/WifiStateMachine(  967): processMsg: DisconnectedState
D/TetherSettings( 5962): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5962): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5962): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5962): Cust_ConnectToPC   : spcsc>false
D/        ( 5962): Cust_ConnectToPC   : IPT>true
D/        ( 5962): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5962): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
E/SmartNS_Utility( 5962): hasRemovableStorageSlot: true
V/NetworkPolicy(  967): updateNotificationsLocked()
D/SmartNS_Utility( 5962): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5962): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  967):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=103936
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=103936
E/WifiStateMachine(  967): Network connection established
D/WifiStateMachine(  967): fetchFrequency(), freq = 2412
E/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  967): acquireWL(1cc50c75): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 967 1000 null
D/CSLegacyTypeTracker(  967): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ActivityManager(  967): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6483 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 19
I/SmartNS_Utility( 5962): setISNotification
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/SmartNS_Utility( 5962): usb_cable_connect = 1
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  967): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/SmartNS_Utility( 5962): usb_denied = 0
,I/SmartNS_PSService( 5962): usb notificaiton:true
E/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
E/ConnectivityService(  967): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  967): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  967): acquireWL(2130240a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
D/Tethering(  967): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  967): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  967): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=4
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  967): NetworkAgent == null
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/NetworkPolicy(  967): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateIfacesLocked()
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 21
V/NetworkPolicy(  967): updateNotificationsLocked()
D/DATA_ICON( 1221): dataConnected: false/false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  967): releaseWL(2130240a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  967): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  967): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  967): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1334): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1334): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1334): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/ConnectivityService(  967): Got NetworkAgent Messenger
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  967): NetworkAgent connected
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1334): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1334): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1334): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  967): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  967): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  967): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  967): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1334): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1334): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
D/wpa_supplicant( 1334): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
V/NetworkPolicy(  967): updateNotificationsLocked()
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1334): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1334): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1334): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): Start Dhcp Watchdog 2
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=147462
E/WifiStateMachine(  967): processMsg: ObtainingIpState
D/SmartNS_Utility( 5962): usb_cable_connect = 1
E/WifiStateMachine(  967):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=103976  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=103976  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  967): processMsg: ConnectModeState
D/SmartNS_Utility( 5962): usb_denied = 0
E/WifiStateMachine(  967):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=103977  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/SmartNS_PSService( 5962): usb notificaiton:true
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131101
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  967):  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  967): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  967): handleMessage: X
D/WIFI    (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  967): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  967): handleMessage: E msg.what=131131
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131155
E/WifiStateMachine(  967): processMsg: ObtainingIpState
I/RemoteViews( 1221): reapply : com.android.settings 2 36
E/WifiStateMachine(  967):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2055] from screen [on:0 period:-1553208072] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1553208071] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967):  get link layer stats 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
I/wpa_supplicant( 1334): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  967): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=77.50 txretriesrate=0.00 rxrate=122.50 userTriggerdPenalty0
E/WifiStateMachine(  967):  good link -> stuck count =0
E/WifiStateMachine(  967):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  967):  isHighRSSI       ---> score=65
E/WifiStateMachine(  967): calculateWifiScore() report new score 60
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: ObtainingIpState
D/ConnectivityService(  967): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  967):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
D/WifiStateMachine(  967): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/PMS     (  967): acquireWL(1091729): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 967 1000 null
E/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  967): handleMessage: E msg.what=196612
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=155,0,0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  967):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=155,0,0
,D/WifiDataStallTracker(  967): setDhcpActive: true
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1334): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  967): do suspend false
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/wpa_supplicant( 1334): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1334): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1334): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1334): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1334): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1334): wlan0: Event DRIVER_GTK_REKEY (37) received
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1334): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1334): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/SmartNS_NSReceiver( 5962): Tethered state change:false isNSOpening:false
D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  967): noteBatchedScanstop()
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c266547 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  967): handleMessage: X
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c266547 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
I/RemoteViews( 1221): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
I/ActivityManager(  967): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6505 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default,
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/ActivityManager(  967): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6526 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  967): acquireWL(8a38aae): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024}
,V/AlarmManager(  967): sending alarm PendingIntent{3277404f: PendingIntentRecord{1e78a3dc com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=104055, Int=0
,D/WISPrService( 5962): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WISPrService( 5962): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
I/ActivityManager(  967): Killing 3153:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  967): killProcessQuiet, pid=3153
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager( 6505): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  967): Recipient 3153
,E/dhcpcd  ( 6547): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6547): version 5.5.6 starting
E/dhcpcd  ( 6547): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6547): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6547): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 6547): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6547): wlan0: sending REQUEST (xid 0xc4340bcc), next in 0.39 seconds
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,I/art     (  967): Explicit concurrent mark sweep GC freed 46122(2MB) AllocSpace objects, 5(292KB) LOS objects, 33% free, 16MB/25MB, paused 2.089ms total 166.945ms
,D/MdProvGlob( 6483): add item 101 (2:g3d1) for 15:android.intent.action.ANY_DATA_STATE
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/CalendarProvider2( 6505): Created com.android.providers.calendar.CalendarAlarmManager@1698a5b4(com.htc.providers.calendar.HtcCalendarProvider@3eb395dd)
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  967): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/CalendarProvider2( 6505): wait start:true
,D/Process (  967): killProcessQuiet, pid=5939,
I/ActivityManager(  967): Killing 5939:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  967): Recipient 5939,
,I/dhcpcd  ( 6547): wlan0: sending REQUEST (xid 0xc4340bcc), next in 2.23 seconds
,D/MdProvGlob( 6483): add item 101 (2:g4d6) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScPhnSt( 6526): [108.2.]  listen tmrbb8,
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 6505): wait end:false
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,I/dhcpcd  ( 6547): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL false Token 22 num clients 8
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,I/dhcpcd  ( 6547): wlan0: leased 192.168.1.130 for 86400 seconds
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
I/dhcpcd  ( 6547): autoip env[11]:autoip=DISABLE
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  967): processMsg: SupplicantStartedState,
,E/WifiStateMachine(  967):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  967): handleMessage: X
D/FlexNetS( 6505): updateSvcAllowedInSettings:false
D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6483): remove item 101 (p4d15in124) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6526): [108.2.] summary 118:p4 ignore
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6483): remove item 101 (p4d1in13) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
D/PMS     (  967): acquireWL(38cedb3f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): releaseWL(8a38aae): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1920): [NET] android_getaddrinfofornet-, err=8
D/MdProvGlob( 6483): remove item 101 (p4d1in20) for 15:android.intent.action.ANY_DATA_STATE
D/wpa_supplicant( 1334): EAPOL: startWhen --> 0
D/wpa_supplicant( 1334): EAPOL: disable timer tick
D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1920): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1920): [NET] android_getaddrinfo_proxy+
D/libc    ( 1920): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1920): [NET] android_getaddrinfo_proxy-, NODATA
D/FlexNetS( 6505): updateSvcAllowedInSettings:false
D/PMS     (  967): acquireWL(38cedb3f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/MdProvGlob( 6483): remove item 101 (p4in14) for 15:android.intent.action.ANY_DATA_STATE,
D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1920): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  967): releaseWL(38cedb3f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,E/WifiStateMachine(  967): handleMessage: E msg.what=131155
E/WifiStateMachine(  967): processMsg: ObtainingIpState
,E/WifiStateMachine(  967):  ObtainingIpState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=77.5, 0.0, 0.0  rx=122.5 bcn=0 [on:0 tx:0 rx:0 period:938] from screen [on:0 period:-1553207127] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=77.5, 0.0, 0.0  rx=122.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1553207126] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967): handleMessage: X
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,D/FlexNetS( 6505): updateSvcAllowedInSettings:false
,I/dhcpcd  ( 6547): bind_interface: daemonise
,D/Process (  967): killProcessQuiet, pid=6214,
I/ActivityManager(  967): Killing 6214:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  967): releaseWL(1091729): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  967): handleMessage: E msg.what=196613
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1334): Power_Mode_Type mode = 0
I/wpa_supplicant( 1334): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1334): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  967): setDhcpActive: false
E/WifiStateMachine(  967): handlePostDhcpSetup release wake lock during DHCP
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  967): WifiStateMachine DHCP successful
E/WifiStateMachine(  967): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  967): link address 192.168.1.130/24
E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  967): gateway: /192.168.1.1
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1334): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1334): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  967): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131210
E/WifiStateMachine(  967): processMsg: ObtainingIpState
E/WifiStateMachine(  967):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1334): wlan0: Control interf,ace command 'SIGNAL_POLL'
,I/wpa_supplicant( 1334): environment dirty rate=0 [4][0][0]
,E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
,D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  967): Recipient 6214
,E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK,
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
,D/wpa_supplicant( 1334): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1334): wlan0: BLACKLIST CLEAR 
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiMonitor(  967): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=45 dispatchEvent: BLACKLIST CLEAR 
D/HtcWifiWanDetect(  967): WAN detection
E/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  967): NetworkAgent != null
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/HtcWifiWanDetect(  967): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  967): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  967): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL true Token 22
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  967):  packet count Tx=158 Rx=246
E/WifiTrafficPoller(  967): notifying of data activity 3
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL true Token 2
E/WifiStateMachine(  967): transitionTo: destState=ConnectedState
E/WifiStateMachine(  967): handleMessage: new destination call exit/enter
E/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL true Token 23
V/NetworkPolicy(  967): mWifiStateReceiver: meteredHint=false,EPS mode=false
,E/WifiStateMachine(  967): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,D/ConnectivityService(  967): Adding iface wlan0 to network 101
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiTrafficPoller(  967):  packet count Tx=158 Rx=246
E/WifiTrafficPoller(  967): notifying of data activity 0
E/WifiStateMachine(  967): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI_ICON( 1221): WifiActivity: 3
,D/WifiDataStallTracker(  967): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  967): updateDataStallInfo: NONE
D/WifiDataStallTracker(  967): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1221): WifiActivity: 0
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 5962): >>>>>WISPrService start isConnected = true<<<<<
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/WifiStateMachine(  967): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/ConnectivityService(  967): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  967): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/ConnectivityService(  967): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  967): handleMessage: X
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
E/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/ConnectivityService(  967): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  967): processMsg: ConnectedState
D/ConnectivityService(  967): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  967): Setting Dns servers for network 101 to [/192.168.1.1]
E/WifiStateMachine(  967):  ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/Nat464Xlat(  967): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  967): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  967): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  967): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  967): handleMessage: X
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  967): handleMessage: E msg.what=131131
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  967): processMsg: ConnectedState
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  967):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  967): currentScore = 0, newScore = 20
E/WifiStateMachine(  967): processMsg: L2ConnectedState
D/ConnectivityService(  967):    accepting network in place of null
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/ConnectivityService(  967): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  967):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  967): handleMessage: X
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
D/WIFI    (  967): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  967): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/CSLegacyTypeTracker(  967): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  967): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WISPrService( 5962): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  967): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  967): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  967): ensureActiveMobilePolicyLocked()
D/Tethering(  967): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  967): acquireWL(c75e955): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
D/ConnectivityService(  967): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/NetworkPolicy(  967): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  967): updateNetworkEnabledLocked()
V/NetworkPolicy(  967): updateIfacesLocked()
,D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  967): Validated
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  967): identical MTU - not setting
,D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
D/Nat464Xlat(  967): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  967): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1221): dataConnected: false/false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/NetworkPolicy(  967): updateNotificationsLocked()
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/PMS     (  967): releaseWL(c75e955): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  967): updateNetworkEnabledLocked()
,V/NetworkPolicy(  967): updateNotificationsLocked()
,D/ConnectivityService(  967): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524295
,D/ConnectivityService(  967): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524295
D/ConnectivityService(  967): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  967): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  967): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/usbnet  (  967):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967): Validated NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  967): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
,D/ConnectivityService(  967): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1221): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
,I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1221): dataConnected: false/false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  967): acquireWL(80a6f6a): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10024}
,V/AlarmManager(  967): sending alarm PendingIntent{305fec5b: PendingIntentRecord{1e78a3dc com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=105389, Int=0
,D/PMS     (  967): acquireWL(3c3d8cf8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(80a6f6a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1920): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1920): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1920): [NET] android_getaddrinfo_proxy+
D/libc    ( 1920): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1920): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  967): acquireWL(26f8c5d1): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
,E/WifiStateMachine(  967): WiFiStateMachine SCAN ALARM
V/AlarmManager(  967): sending alarm PendingIntent{3eebdeb9: PendingIntentRecord{246062fe android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454440706752, Int=20000
E/WifiStateMachine(  967): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
E/WifiStateMachine(  967): processMsg: ConnectedState
,D/PMS     (  967): releaseWL(26f8c5d1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  967):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:2169 rssi=-58 f=2412 sc=60 link=72 tx=77.5, 0.0, 0.0  rx=122.5 fiv=40000 [on:0 tx:0 rx:0 period:536] from screen [on:0 period:-1553206589]
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2169 rssi=-58 f=2412 sc=60 link=72 tx=77.5, 0.0, 0.0  rx=122.5 fiv=40000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1553206589]
E/WifiStateMachine(  967): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=77.50 rxSuccessRate=122.50 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-58
E/WifiStateMachine(  967): WifiStateMachine CMD_START_SCAN with age=8729 interval=40000 maxinterval=300000
E/WifiStateMachine(  967): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  967): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=77.50 rx=122.50
E/WifiStateMachine(  967): handleMessage: X
,D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1920): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1920): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  967): acquireWL(34d81836): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1920 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1920): Connected
D/PMS     (  967): releaseWL(3c3d8cf8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(34d81836): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(726f337): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1920): Message class com.google.f.a.a.p
,D/PMS     (  967): releaseWL(726f337): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/CalendarProvider2( 6505): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6505): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  967): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6600 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/Process (  967): killProcessQuiet, pid=6237,
I/ActivityManager(  967): Killing 6237:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  410): Explicit concurrent mark sweep GC freed 8665(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 263us total 16.367ms
,I/art     (  410): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 220us total 14.059ms,
,I/art     (  410): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 219us total 13.348ms
,I/ActivityManager(  967): Recipient 6237,
,W/ResourcesManager( 6600): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6600): onCreate,
D/ProviderChangeReceiver( 6600): ---------------------------------------------------
D/ProviderChangeReceiver( 6600): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  967): killProcessQuiet, pid=6027,
I/ActivityManager(  967): Killing 6027:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6600): start to updateAlertNotification!
,I/ActivityManager(  967): Recipient 6027
,D/HtcAlertService( 6600): No fired or scheduled alerts
,D/HtcAlertUtils( 6600): -- cancelReminderNotification --
D/HtcAlertUtils( 6600): broadcastExistReminder!
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  967): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6623 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  967): acquireWL(3d3a80a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{10076}
V/AlarmManager(  967): sending alarm PendingIntent{7f2ee0d: PendingIntentRecord{120581c2 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454440707468, Int=60000,
D/PMS     (  967): releaseWL(3d3a80a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  967):  packet count Tx=168 Rx=257
D/WIFI_ICON( 1221): WifiActivity: 3,
,E/WifiTrafficPoller(  967): notifying of data activity 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/SMSBackup( 6623): SMSBackupAgentService started
D/SMSBackup( 6623): Checking restore status
,D/SMSBackup( 6623): Restore complete
D/SMSBackup( 6623): cancelCheckAlarm
,D/SMSBackup( 6623): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  967): killProcessQuiet, pid=6268
I/ActivityManager(  967): Killing 6268:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  967): releaseWL(1cc50c75): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  967): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  967): Recipient 6268,
,D/AccTypeManager( 1739): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
D/PMS     (  967): acquireWL(bed5e09): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5199 10112 null
W/SystemReader(  967): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1739): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  967): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/Prism.ItemManager( 1544): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
I/Prism.ItemManager( 1544): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1544): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Launcher( 1544): Deferring update until onResume
D/Launcher( 1544): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1739): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,D/PMS     (  967): releaseWL(bed5e09): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PhoneApp( 1491): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/[PluginManager]RegisterService( 1613): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1613): handle notify Blinkfeed plugin client changed
,E/ExternalAccountType( 1739): Unsupported attribute readOnly
,D/PackageBroadcastService( 4419): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/PMS     (  967): acquireWL(1f0d540f): PARTIAL_WAKE_LOCK  AsyncService 0x1 6053 10167 null
,D/PMS     (  967): releaseWL(1f0d540f): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,I/PackageBroadcastService( 4419): Null package name or gms related package.  Ignoreing.
,D/PMS     (  967): acquireWL(307e9a7a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6053 10167 null
,D/PMS     (  967): releaseWL(307e9a7a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/PMS     (  967): acquireWL(15ead688): PARTIAL_WAKE_LOCK  Icing 0x1 4419 10024 WorkSource{10024 com.google.android.gms}
,I/UpdateIcingCorporaServi( 5907): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 4419): updateResources: need to parse f{com.google.android.gms}
,D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ConnectivityHelper( 1544): [onReceive] WIFI(1): CONNECTED
,D/PMS     (  967): releaseWL(15ead688): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  967): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6656 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/PackageManager(  967): Unable to load service info ResolveInfo{52d361e com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  967): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  967): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  967): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  967): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  967): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  967): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  967): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  967): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  967): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  967): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  967): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  967): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/WifiStateMachine(  967): handleMessage: E msg.what=131155
,E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=77.5, 0.0, 0.0  rx=122.5 bcn=0 [on:0 tx:0 rx:0 period:1527] from screen [on:0 period:-1553205061] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
,E/WifiStateMachine(  967):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=77.5, 0.0, 0.0  rx=122.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553205058] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
,E/WifiStateMachine(  967):  get link layer stats 0,
,W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1334): environment dirty rate=8 [12][1][0]
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiStateMachine(  967): BroadcastRSSIForIMS, newrssi =-58 , oldRssi= -200
I/UpdateIcingCorporaServi( 5907): UpdateCorporaTask done [took 61 ms] updated apps [took 61 ms] 
E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  967): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=45.25 txretriesrate=0.00 rxrate=67.25 userTriggerdPenalty0
E/WifiStateMachine(  967):  good link -> stuck count =0
E/WifiStateMachine(  967):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  967):  isHighRSSI       ---> score=65
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  967): handleMessage: X
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/MdScPhnSt( 6526): [f8.1.]  listen tmrbb8
,V/GmsNetworkLocationProvi( 1832): DISABLE,
,D/MdScDataSum( 6526): [f8.1.] summary 118:p1 ignore
,I/GCoreNlp( 1832): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  967): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
D/PMS     (  967): acquireWL(e11c066): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
,D/GpsLocationProvider(  967): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  967): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  967): [AlarmQueuing] connectivity wifi: false
D/htcCheckinService(  967): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
,E/GpsLocationProvider(  967): No APN found to select.
,D/PMS     (  967): releaseWL(e11c066): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
D/PMS     (  967): acquireWL(2a697cf2): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 967 1000 null
,D/PMS     (  967): releaseWL(2a697cf2): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/LocationProviderProxy(  967): applying state to connected service
D/PMS     (  967): acquireWL(260e763e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1832 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(260e763e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  967): applying state to connected service
,D/PMS     (  967): acquireWL(e236c9f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1832 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(e236c9f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): acquireWL(3810f16): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1832 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): releaseWL(3810f16): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/MusicStore( 6656): Database version: 120,
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 24 num clients 8
,D/WIFI_ICON( 1221): WifiActivity: 0
E/WifiTrafficPoller(  967):  packet count Tx=168 Rx=257
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  967): notifying of data activity 0
,D/VoldConnector(  967): SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6656): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  967): SND -> {29 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6656): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  967): SND -> {30 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6656): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6656): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6656): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6656): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6656): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6656): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15247828: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6656): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6656): GMSCore installation verified,
,I/ConfigStore( 6656): Config Database version: 1,
,I/art     ( 1920): Explicit concurrent mark sweep GC freed 14083(783KB) AllocSpace objects, 9(628KB) LOS objects, 49% free, 4MB/8MB, paused 652us total 35.660ms
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6656, uid=10159, userID:0,
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
,D/MediaRouterService(  967): Client com.google.android.music (pid 6656): Registered,
,D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
,I/MediaRouter( 6656): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6656): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6656): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6656): type=WIFI subType= reason=null isConnected=true,
,D/AutoSetting( 1613): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6656, uid=10159, userID:0,
,D/AutoSetting( 1613): service - onCreate()
,D/MobileConnectivityChangeReceiver( 6374): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6374): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1613): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
D/AutoSetting( 1613): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1613): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1613): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1613): service - handleMessage() setting current location null
,D/LocationManagerService(  967): request 32f6625e passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,I/GHttpClientFactory( 6656): Using our fixed implementation of GMSCore's GoogleHttpClient,
,I/GoogleURLConnFactory( 6656): Using platform SSLCertificateSocketFactory,
,D/ChimeraCfgMgr( 4419): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4419): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc    ( 5199): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5199): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 5199): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024,
I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6702 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/libc    ( 5199): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5199): [NET] android_getaddrinfo_proxy+
D/libc    ( 5199): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5199): [NET] android_getaddrinfo_proxy-, success
I/GLSUser ( 1920): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1920): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1920): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1920): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1920): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4419): [AccountUtils] Account not ready,
W/Kids    ( 4419): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.d(SourceFile:599)
,W/Kids    ( 4419): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4419): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4419): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4419): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4419): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40,
,D/VoldConnector(  967): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6702): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  967): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6702): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6702): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6702):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6702):   adb logcat -s GAv4
,D/VoldConnector(  967): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6702): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6702): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/VoldConnector(  967): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6702): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6702): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6702): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/art     (  967): Explicit concurrent mark sweep GC freed 39717(2MB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/25MB, paused 1.976ms total 140.933ms,
,W/global  ( 6702): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6702): [apache-http] Connection GC has been deprecated!
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  967): [NET] android_getaddrinfofornet-, err=8
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+
D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  967):  packet count Tx=174 Rx=262
D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  967): notifying of data activity 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/HtcWifiWanDetect(  967): Find DNS Address www.htc.com/23.59.123.86,
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/libc    (  967): [NET] android_getaddrinfo_proxy-, success
D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  967): acquireWL(e529947): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
I/AlarmManager(  967): [AlarmQueuing] connectivity wifi: true
D/PMS     (  967): acquireWL(17c91574): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 967 1000 null
,I/ConnectivityHelper( 1544): [onReceive] WIFI(1): CONNECTED
,D/PMS     (  967): releaseWL(17c91574): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  967): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  967): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  967): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/NetworkMonitor( 6656): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  967): No APN found to select.
,D/PMS     (  967): releaseWL(e529947): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6526): [ee6.1.]  listen tmrbb8,
,D/MdScDataSum( 6526): [ee6.1.] summary 118:p1 ignore
,I/WebViewFactory( 6702): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6702): Time to load native libraries: 2 ms (timestamps 8368-8370),
I/LibraryLoader( 6702): Expected native library version number "",actual native library version number ""
,I/Prism.ItemManager( 1544): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1544): loadItems() com.htc.launcher.pageview.WidgetManager@b7d056d +
I/Prism.WidgetManager( 1544): onLoadItems() +
V/WebViewChromiumFactoryProvider( 6702): Binding Chromium to main looper Looper (main, tid 1) {2574661}
,I/LibraryLoader( 6702): Expected native library version number "",actual native library version number ""
,I/chromium( 6702): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/ResourcesManager( 1544): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/BrowserStartupController( 6702): Initializing chromium process, singleProcess=true,
,W/art     ( 6702): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6702): ApplicationContext is null in ApplicationStatus
,W/chromium( 6702): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6702): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6702): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6702): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6702): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6702): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6702): Local Branch: 
I/Adreno-EGL( 6702): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6702): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6702):                  d74aa161a12b9c6fc6332151
,E/WifiDataStallTracker(  967): DATA_MONITOR_POLL true Token 3
,W/AudioManagerAndroid( 6702): Requires BLUETOOTH permission
I/NSApplication( 6702): Starting up...
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6766 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/art     (  409): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 167us total 19.005ms
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 151us total 15.693ms
,W/ResourcesManager( 1544): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 17.346ms
,W/asset   ( 1544): Copying FileAsset 0x55a90a3de0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1544): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1544): onLoadItems() -
I/Prism.ItemManager( 1544): loadItems() com.htc.launcher.pageview.WidgetManager@b7d056d -
,E/WifiStateMachine(  967): handleMessage: E msg.what=131168,
E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  967): handleMessage: X
,D/PhoneApp( 1491): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1491): -- N1 =0
,D/PhoneApp( 1491): -- N2 =0
,D/PhoneApp( 1491): -- N3 =0,
,D/Process (  967): killProcessQuiet, pid=5729,
I/ActivityManager(  967): Killing 5729:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  967): Recipient 5729
,V/MusicLeanback( 6656): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6374): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6374): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1613): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1613): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1613): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1613): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1613): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1613): service - handleMessage() setting current location null
,I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4419, uid=10024, userID:0
,D/ChimeraCfgMgr( 4419): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4419): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  967):  packet count Tx=176 Rx=263
,I/GLSUser ( 1920): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1920): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1920): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1920): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1920): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4419): [AccountUtils] Account not ready,
W/Kids    ( 4419): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4419): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4419): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4419): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4419): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4419): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4419): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6418): 
,E/WifiStateMachine(  967): handleMessage: E msg.what=131155,
E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=45.2, 0.0, 0.0  rx=67.2 bcn=0 [on:0 tx:0 rx:0 period:2997] from screen [on:0 period:-1553202036] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
,E/WifiStateMachine(  967):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=45.2, 0.0, 0.0  rx=67.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1553202034] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967):  get link layer stats 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1334): environment dirty rate=11 [9][1][0]
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
,E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  967): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=27.12 txretriesrate=0.00 rxrate=37.12 userTriggerdPenalty0
E/WifiStateMachine(  967):  good link -> stuck count =0
E/WifiStateMachine(  967):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  967):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  967): handleMessage: X
,E/WifiDataStallTracker(  967): DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  967): updateDataStallInfo: mDataStallTxRxSum={txSum=150 rxSum=134} preTxRxSum={txSum=0 rxSum=0},
D/WifiDataStallTracker(  967): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  967): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6418): 
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  967):  packet count Tx=177 Rx=264
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6418): 
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 6418): 
,I/jxcore-log( 6418): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6418): 
,I/PMS     (  967): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  967): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3a0e484
W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  967): disable: get sensor name = Accelerometer Sensor
W/PMN     (  967): goingToSleep
W/SensorService(  967): pid=967, uid=1000
W/SensorService(  967): Active sensors: size = 4
,W/SensorService(  967): Accelerometer Sensor (handle=0x00000000, connections=1)
,W/SensorService(  967): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  967): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3a0e484, eanble = 0, strlen(mName) = 90
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  967): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@420020f
W/SensorService(  967): Listener[1] = com.htc.smartdim.sensor_eye@52c123
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  967): mWirelessDisplayManager is null
D/PMS     (  967): acquireWL(33401a72): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 967 1000 null
W/PMS     (  967): mWirelessDisplayManager is still null
,W/PMN     (  967): goingToSleep done
,I/PMS     (  967): Sleeping (uid 1000)...,
W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/XAN-DPS (  967): prepareColorFade 1
,D/PMS     (  967): releaseWL(33401a72): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  967): ACTION_SCREEN_ON
,I/AlarmManager(  967): [AlarmQueuing] recover blocked alarms
,I/AlarmManager(  967): [AlarmQueuing] done recovering
I/AlarmManager(  967): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  967): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL true Token 24
E/WifiTrafficPoller(  967):  packet count Tx=177 Rx=265
E/WifiTrafficPoller(  967): notifying of data activity 1
,E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  967): updateDataStallInfo: mDataStallTxRxSum={txSum=150 rxSum=134} preTxRxSum={txSum=150 rxSum=134}
D/WifiDataStallTracker(  967): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  967): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,I/Adreno-EGL(  967): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  967): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  967): Build Date: 03/09/15 Mon
,I/Adreno-EGL(  967): Local Branch: 
I/Adreno-EGL(  967): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  967): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  967):                  d74aa161a12b9c6fc6332151
,E/WifiStateMachine(  967): handleMessage: E msg.what=131167
,E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
,E/WifiStateMachine(  967):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
,E/WifiStateMachine(  967):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  967):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
D/WIFI_ICON( 1221): WifiActivity: 1
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1334): SET_SCREEN_ON:On
I/wpa_supplicant( 1334): htc_wext_set_keepalive +
I/wpa_supplicant( 1334): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1334): getPrivFuncNum +	
I/wpa_supplicant( 1334): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1334): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1334): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1334): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1334): htc_wext_set_TX_TRACKING - ret = 0
,E/WifiStateMachine(  967): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
,D/WifiStateMachine(  967): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  967): handleScreenStateChanged Exit: true
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SIGNAL_POLL'
V/SRS_Proc(  401): ParamSet string: screen_state=on
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  967): handleMessage: E msg.what=155650
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,D/NetworkPolicy(  967): updateScreenOn: false
,V/NetworkPolicy(  967): updateIfacesLocked()
I/wpa_supplicant( 1334): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  967): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
,E/WifiConfigStore(  967): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  967): handleMessage: X
D/WifiWatchdogStateMachine(  967): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  967): handleMessage: E msg.what=131127
E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  967): processMsg: L2ConnectedState
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
E/WifiStateMachine(  967):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
,E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131129
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1334): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1334): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  967): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
,E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=46 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  967): handleMessage: X
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/ActivityManager(  967): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6804 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL true Token 25 num clients 8
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false),
,D/XAN-DPS (  967): prepareColorFade done,
D/XAN-DPS (  967): setBrightness to 0
I/SensorManager(  967): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@420020f
W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
W/ContextImpl( 6804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
W/SensorService(  967): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  967): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,W/SensorService(  967): pid=967, uid=1000
W/SensorService(  967): Active sensors: size = 3
W/SensorService(  967): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  967): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  967): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@420020f, eanble = 0, strlen(mName) = 66
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  967): Listener[0] = com.htc.smartdim.sensor_eye@52c123
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
,V/ActivityManager(  967): Display changed displayId=0
D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
D/PMS     (  967): acquireWL(71add35): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1832 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(1d485ca): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1832 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6804): MY_DEBUG = false,
,D/PMS     (  967): releaseWL(1d485ca): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): releaseWL(71add35): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/SmartSyncUtils( 6804): isEpsOn(), nState = 0,
,D/PMS     (  967): acquireWL(2a567a58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6804 1000 null
,D/PMS     (  967): releaseWL(2a567a58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/AlarmManager(  967): ACTION_SCREEN_OFF,
I/AlarmManager(  967): [AlarmQueuing] screen off now: 
,I/AlarmManager(  967): [AlarmQueuing] data connection: true
I/AlarmManager(  967): [AlarmQueuing] wifi connection: true
E/WifiTrafficPoller(  967): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/WifiDataStallTracker(  967): stopDataStallAlarm 
E/WifiDataStallTracker(  967): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  967): handleMessage: E msg.what=131167
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  967):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  967): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1334): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1334): SET_SCREEN_ON:Off
I/wpa_supplicant( 1334): htc_wext_set_keepalive +
I/wpa_supplicant( 1334): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1334): getPrivFuncNum +	
I/wpa_supplicant( 1334): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1334): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1334): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1334): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1334): htc_wext_set_keepalive - ret = 0
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/WifiStateMachine(  967): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiDisplayAdapter(  967): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  967):     Client/Owner: Client
D/WifiDisplayAdapter(  967):     GroupId: 
D/WifiDisplayAdapter(  967):     Passphrase: 
D/WifiDisplayAdapter(  967):     SessionId: 0
D/WifiDisplayAdapter(  967):     IP Address: }
,D/WifiStateMachine(  967): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  967): handleScreenStateChanged Exit: false
E/WifiStateMachine(  967): handleMessage: X
E/WifiStateMachine(  967): handleMessage: E msg.what=131154
E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  967): handleMessage: X
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  967): Init customizeScreenOffDelayClass error
D/WifiController(  967): handleMessage: E msg.what=155651
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,D/NetworkPolicy(  967): updateScreenOn: false
V/NetworkPolicy(  967): updateIfacesLocked()
D/NetworkManagementService(  967): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@2205eaf4, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  967): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  967): pid=1221, uid=10041
W/SensorService(  967): Active sensors: size = 4
,W/SensorService(  967): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  967): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@2205eaf4, eanble = 1, strlen(mName) = 57
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  967): Listener[0] = com.htc.smartdim.sensor_eye@52c123
W/SensorService(  967): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@2205eaf4
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1311): [EventService] getTotalRam: 1842 Mb,
D/GpsLocationProvider(  967): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1491): start background delete task...
,D/PMS     (  967): acquireWL(182917b1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1832 10024 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1491): size: 0 , 0
D/PMS     (  967): releaseWL(182917b1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1491): Background delete complete
W/ContextImpl( 6804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  967): acquireWL(129d3496): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1832 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  967): releaseWL(129d3496): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/SmartSyncUtils( 6804): isEpsOn(), nState = 0,
,D/SmartSyncUtils( 6804): isEpsOn(), nState = 0
,W/ContextImpl( 6804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
,I/SensorManager(  967): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@52c123,
,W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  967): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  967): pid=967, uid=1000
,W/SensorService(  967): Active sensors: size = 3
W/SensorService(  967): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@52c123, eanble = 0, strlen(mName) = 34
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  967): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2205eaf4
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  967): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  967): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  967): pid=967, uid=1000,
W/SensorService(  967): Active sensors: size = 2
W/SensorService(  967): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  967): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  967): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@52c123, eanble = 0, strlen(mName) = 34
W/SensorService(  967): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  967): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@2205eaf4
W/SensorService(  967): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  967): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@52c123
,E/ActivityThread(  967): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1e271620 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  967): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1e271620 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  967): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  967): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  967): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  967): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  967): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  967): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  967): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  967): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  967): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  967): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  967): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  967): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  967): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  967): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  967): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  967): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  967): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  967): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/AutoSetting( 1613): service - mHandler: cancel location update
D/AutoSetting( 1613): service -           changes count: 0
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145),
,I/PowerUsageList:PowerUsageHelper( 6804): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/RemoteViews( 1221): apply : com.htc.updater 1 10 1 36,
,D/SmartSyncUtils( 6804): getMobilePolicyEnabled, result = true
,D/WifiService(  967): New client listening to asynchronous messages
E/WifiTrafficPoller(  967): ADD_CLIENT: 9
,D/PowerUsageList:BatterySipperExt( 6804): gen(), null == sipper.uidObj, userId = 0
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  967): Excessive delay in setPowerMode(): 271ms,
D/PMS     (  967): Setting HAL interactive mode to false
W/HtcSystemUPManager(  967): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006,
D/PMS     (  967): Setting HAL interactive mode to false done
D/PMS     (  967): Setting HAL auto-suspend mode to true
D/PMS     (  967): Setting HAL auto-suspend mode done
I/InputMethodManagerService(  967): screenObserver, isScreenOn=false
D/StatusBarManagerService(  967): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  967): Disable input method client, pid=6418
,I/InputMethodManager( 6418): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{267ac26f VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@8b6aa11,
,D/HABCtrl (  967): TPE algorithm. remove timeout.
,D/PMS     (  967): acquireWL(30067ded): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(30067ded): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/InputManager(  967): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
,D/PMS     (  967): OOBE c monitor 11
I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,D/NfcService( 1508): ScreenObserver: OFF
D/NfcService( 1508): applyRouting - 0
D/HtcPowerSaver(  967): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PMS     (  967): acquireWL(3f700422): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1508 1027 null
,D/NfcService( 1508): applyRouting -2
D/NfcService( 1508): applyRouting
D/NfcService( 1508): Ignore this applyRouting...
,D/PMS     (  967): releaseWL(3f700422): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  967): << updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
,D/WifiController(  967): handleMessage: X
,I/ClockController( 1221): stop clock update:screen off,
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PowerUsageList:PowerUsageHelper( 6804): MY_DEBUG = false,
,D/Process (  967): killProcessQuiet, pid=5525
I/ActivityManager(  967): Killing 5525:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5525
,D/Process (  967): killProcessQuiet, pid=6323
I/ActivityManager(  967): Killing 6323:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6323
,E/WifiTrafficPoller(  967): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,D/Process (  967): killProcessQuiet, pid=6600
I/ActivityManager(  967): Killing 6600:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6600
,D/PMS     (  967): acquireWL(1cce3c70): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6656 10159 null
,D/WearableService( 5027): callingUid 10024, callindPid: 5027
I/PackageManager(  967):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6656, uid=10159, userID:0
,I/MusicLeanback( 6656): Conditions not met for autocaching. okToAttempt=false
,D/PMS     (  967): releaseWL(1cce3c70): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6656): Stop autocaching.
,E/GmsUtils( 6656): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6656): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PMS     (  967): releaseWL(106cffd6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,E/WifiStateMachine(  967): handleMessage: E msg.what=131155,
E/WifiStateMachine(  967): processMsg: ConnectedState
,E/WifiStateMachine(  967):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553199012] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1553199008] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  967): handleMessage: X
,E/WifiStateMachine(  967): handleMessage: E msg.what=131155,
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1156] from screen [on:0 period:-1553197850] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967): processMsg: L2ConnectedState,
E/WifiStateMachine(  967):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1553197848] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  967): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  967): DATA_MONITOR_POLL false Token 5,
,I/jxcore-log( 6418): Test app app.js loaded,
I/jxcore-log( 6418): 
,I/chromium( 6418): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6418): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37bdc776 added. We now have 1 listener(s)
D/BluetoothAdapter( 6418): 530085022: getState(). Returning 12
I/jxcore-log( 6418): BLE advertisement is supported
I/jxcore-log( 6418): 
,E/WifiDataStallTracker(  967): DATA_MONITOR_POLL false Token 5,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/ActivityManager(  967): Killing 5633:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  967): killProcessQuiet, pid=5633
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5633
,D/PMS     (  967): acquireWL(2b7a4aa3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
,V/AlarmManager(  967): sending alarm PendingIntent{2865b1e2: PendingIntentRecord{264bc973 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=138711, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{22e1a1a0: PendingIntentRecord{3b10c159 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141505, Int=0
,D/WeatherUtility( 1221): Weather sync is On
D/PMS     (  967): releaseWL(2b7a4aa3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/AutoSetting( 1613): service - handleMessage() stop self,
,D/AutoSetting( 1613): service - onDestroy() END
,D/AutoSetting( 1613): service - handleMessage() quit looper
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/WifiStateMachine(  967): handleMessage: E msg.what=131165,
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: ConnectModeState
E/WifiStateMachine(  967):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: DriverStartedState
E/WifiStateMachine(  967):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/WifiStateMachine(  967):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
E/WifiStateMachine(  967): processMsg: DefaultState
E/WifiStateMachine(  967):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  967): handleMessage: X
,D/GpsLocationProvider(  967): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  967): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  967): acquireWL(24e1a11e): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 967 1000 null,
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  967): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  967): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  967): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  967): [NET] android_getaddrinfo_proxy+,
D/libc    (  967): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  967): [NET] android_getaddrinfo_proxy-, success,
,D/libc    (  967): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
D/libc    (  967): [NET] android_getaddrinfofornet-, SUCCESS,
,D/GpsLocationProvider(  967): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  967): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  967): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  967):  [handleDownloadXtraData]inject done.
D/PMS     (  967): acquireWL(2302b12a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 967 1000 null
D/GpsLocationProvider(  967): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  967): releaseWL(24e1a11e): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  967): releaseWL(2302b12a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/WifiStateMachine(  967): handleMessage: E msg.what=131326,
E/WifiStateMachine(  967): processMsg: ConnectedState
E/WifiStateMachine(  967):  ConnectedState what:131326 2 0
E/WifiStateMachine(  967): processMsg: L2ConnectedState
E/WifiStateMachine(  967):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  967): handleMessage: X
,D/PMS     (  967): acquireWL(2a9c6b1b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
D/UsbnetService(  967): BroadcastReceiver::onReceive+
I/BatteryService(  967): n_update end
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): releaseWL(2a9c6b1b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/NotificationService(  967): plugged=true pluggin=true,
D/WifiController(  967): handleMessage: E msg.what=155652
D/PMS     (  967): runPSCheck
D/WifiController(  967): processMsg: DeviceActiveState
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: StaEnabledState
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): battery changed pluggedType: 2
,D/WifiController(  967): handleMessage: X
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1491): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  967): acquireWL(3f1e04b8): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{23884291: PendingIntentRecord{3272b5f6 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454440768447, Int=0
D/PMS     (  967): acquireWL(208c9df7): PARTIAL_WAKE_LOCK  *backup* 0x1 967 1000 null
,V/AlarmManager(  967): sending alarm PendingIntent{2865b1e2: PendingIntentRecord{264bc973 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=198710, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{180ab464: PendingIntentRecord{28dd76cd android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202269, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{100c3b82: PendingIntentRecord{17e32293 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454440708412, Int=1800000
V/AlarmManager(  967): sending alarm PendingIntent{30f0b2d0: PendingIntentRecord{9d7b2c9 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190049, Int=0
,W/BackupManagerService(  967): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  967): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  967): releaseWL(208c9df7): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  967): acquireWL(39c68dce): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4419 10024 WorkSource{10024 com.google.android.gms},
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  967): releaseWL(3f1e04b8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/PMS     (  967): acquireWL(ff62bfc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): acquireWL(e1fb285): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4419 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(39c68dce): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(3c1b8da): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(ff62bfc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/EventLogService( 4419): Aggregate from 1454440698074 (log), 1454438908375 (data)
,V/GLSActivity( 1920): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  967): releaseWL(3c1b8da): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): acquireWL(4e9d683): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(4e9d683): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  967): acquireWL(33e7000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(e1fb285): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(7b5e039): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(3c6957df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(33e7000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): acquireWL(130b46f5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(130b46f5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1920): Using platform SSLCertificateSocketFactory,
,I/VacuumService( 1920): Vacuum at: now=1454440804005 tag=VacuumService
,D/PMS     (  967): releaseWL(3c6957df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(30e25fad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(30e25fad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(3657a2e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(3657a2e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  967): acquireWL(33bd6673): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(7b5e039): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(2ccdd930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(33bd6673): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(19510b2e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(19510b2e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(c7df6cf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1920): Using platform SSLCertificateSocketFactory
,D/PMS     (  967): releaseWL(c7df6cf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1920): No account for auth token provided,
,D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1920): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1920): [NET] android_getaddrinfofornet-, pass to proxy,
,D/libc    ( 1920): [NET] android_getaddrinfo_proxy+
D/libc    ( 1920): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1920): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1920): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1920): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1920): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1920): No account for auth token provided
,W/Uploader( 1920):  no longer exists, so no auth token.,
,W/Uploader( 1920): No account for auth token provided,
,W/Uploader( 1920): No account for auth token provided,
,W/Uploader( 1920): No account for auth token provided,
,D/PMS     (  967): releaseWL(2ccdd930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(66ac3a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): releaseWL(66ac3a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  967): acquireWL(230d30eb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(230d30eb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1613): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2f02bf3f,
,D/Process (  967): killProcessQuiet, pid=6623
I/ActivityManager(  967): Killing 6623:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 6623,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/wpa_supplicant( 1334): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1334): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1334): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  967): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,D/PMS     (  967): acquireWL(32479e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(32479e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): runPSCheck
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...
,D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): handleMessage: X
,I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  967): acquireWL(2e6884e1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000}
,V/AlarmManager(  967): sending alarm PendingIntent{2865b1e2: PendingIntentRecord{264bc973 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=258711, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{150bf0c7: PendingIntentRecord{1a5c56f4 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454440940350, Int=0
,D/PMS     (  967): releaseWL(2e6884e1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  967): acquireWL(10878e1d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(10878e1d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/NotificationService(  967): plugged=true pluggin=true
,D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): handleMessage: E msg.what=155652
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  967): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  967): << updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1920): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  967): Explicit concurrent mark sweep GC freed 42666(2MB) AllocSpace objects, 5(1116KB) LOS objects, 33% free, 18MB/28MB, paused 1.924ms total 213.306ms,
,I/GLSUser ( 1920): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1920): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1920): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1920): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1920): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1920): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1920): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1920): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1920): ,	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1920): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1920): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1920): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5986): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5986): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5986): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5986): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5986): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5986): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5986): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5986): Ignoring header User-Agent because its value was null.,
,D/libc    ( 5986): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5986): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5986): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5986): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5986): [NET] android_getaddrinfo_proxy+
D/libc    ( 5986): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5986): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  967): acquireWL(8c99b7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(8c99b7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  967): plugged=true pluggin=true
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  967): acquireWL(2d3d6524): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(2d3d6524): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1221): closing low battery warning: level=100
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  967): plugged=true pluggin=true
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  967): acquireWL(15cd388d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  967): n_update end
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  967): releaseWL(15cd388d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  967): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
,D/PMS     (  967): runPSCheck
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: StaEnabledState
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  967): processMsg: DefaultState
I/HtcPowerSaver(  967): << updateStatus
,D/WifiController(  967): handleMessage: X
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  476): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  967): acquireWL(19aa3a42): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(19aa3a42): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  967): updateBatteryInfo,
D/PMS     (  967): runPSCheck
D/HtcPowerSaver(  967): Checking...
I/HtcPowerSaver(  967): >> updateStatus
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
,D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1491): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1491): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1491): sku_id=118
,D/ContactMessageStore( 1491): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1491): start background delete task...
,D/ContactMessageStore( 1491): size: 0 , 0,
D/ContactMessageStore( 1491): Background delete complete
,D/PMS     (  967): acquireWL(1c471a53): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
,I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(1c471a53): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  967): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): acquireWL(237daf90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
D/UsbnetService(  967): onReceive BATTERY_CHANGED
I/BatteryService(  967): n_update end
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  967): releaseWL(237daf90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/NotificationService(  967): plugged=true pluggin=true
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  967): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: DefaultState
D/HtcPowerSaver(  967): updateBatteryInfo
,D/WifiController(  967): handleMessage: X
D/PMS     (  967): runPSCheck
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  967): Checking...
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  967): >> updateStatus
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(161d089): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{2865b1e2: PendingIntentRecord{264bc973 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=378711, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{3725b88e: PendingIntentRecord{51f08af com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=939191, Int=0
,I/bt-btm  ( 3026): Received oneshot timer event complete
D/PMS     (  967): acquireWL(93634bc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3026 1002 null
I/bt-btm  ( 3026): btm_ble_timeout
I/bt-btm  ( 3026): btm_gen_resolvable_private_addr
,D/PMS     (  967): releaseWL(161d089): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/bt-btm  ( 3026): btm_ble_rand_enc_complete
I/bt-btm  ( 3026): btm_gen_resolve_paddr_low
D/bt-smp  ( 3026): smp_encrypt_data
W/bt-smp  ( 3026): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3026): Plain text(LSB ~ MSB) = 4b 56 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3026): Encrypted text(LSB ~ MSB) = 67 4d b0 bd a2 e1 65 30 25 dd 70 eb dd 29 86 4f 
I/bt-btm  ( 3026): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3026): Stopping oneshot timer
D/bt-btm  ( 3026): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  967): releaseWL(93634bc): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  967): acquireWL(358dec45): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(358dec45): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/NotificationService(  967): plugged=true pluggin=true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  967): BroadcastReceiver::onReceive-
,D/PMS     (  967): runPSCheck
D/WifiController(  967): handleMessage: E msg.what=155652
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: DeviceActiveState
I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(dc8cf9a): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{49858cf: PendingIntentRecord{1f07125c android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804467, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{2865b1e2: PendingIntentRecord{264bc973 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=978711, Int=0
,V/AlarmManager(  967): sending alarm PendingIntent{38dd80cb: PendingIntentRecord{1b8fe0a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1005687, Int=0,
,I/ActivityManager(  967): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6877 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  967): sending alarm PendingIntent{3ca607c1: PendingIntentRecord{29544b66 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454441529755, Int=0
V/AlarmManager(  967): sending alarm PendingIntent{3ec15ea7: PendingIntentRecord{22eabb41 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454441569075, Int=0
D/PMS     (  967): acquireWL(3f565f54): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  967): releaseWL(3f565f54): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  967): releaseWL(dc8cf9a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
D/PowerUsageList:PowerUsageHelper( 6804): MY_DEBUG = false
,D/PowerUsageService( 6804): repeat time = 1454442507054
,D/PMS     (  967): acquireWL(3ec9b7f2): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1920 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1920): Message class com.google.f.a.a.i
,D/PMS     (  967): releaseWL(3ec9b7f2): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6804): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6804): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 6899): Error opening trace file: Permission denied (13),
I/dex2oat ( 6899): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6899): dex2oat: override thread count:4
,I/dex2oat ( 6899): dex2oat took 966.694ms (threads: 4),
,I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): VersionName:             1.2.853019,
I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk,
I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6877): ApplicationMonitor {37a5fb7f}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6877): PnsModel {1f98749e}: update(): Update registration caused by: alarm,
,I/PushClient( 6877): PnsConfigModel {2deab04d}: <init>(): Use dm-client for provisioning.
,W/System.err( 6877): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6877): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6877): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6877): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  967): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6906 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6906): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6906 dbg=false s=true
,I/DeviceManagement( 6906): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6906): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6906): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6906): WorkflowService: Starting workflow service
,I/DeviceManagement( 6906): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@10d8b2d9] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6906): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6906): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6906): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6906): SessionStateController: Checking invariants...
,I/DeviceManagement( 6906): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6906): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6906): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6906): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@10d8b2d9]
,I/DeviceManagement( 6906): WorkflowService: Stopping workflow service,
,D/Process (  967): killProcessQuiet, pid=5962
I/ActivityManager(  967): Killing 5962:com.android.settings/1000 (adj 15): empty #17
D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/WifiService(  967): Client connection lost with reason: 4,
I/ActivityManager(  967): Recipient 5962
,I/PushClient( 6877): PnsModel {1f98749e}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  967): killProcessQuiet, pid=5986
I/ActivityManager(  967): Killing 5986:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  967): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  967): Recipient 5986
,D/PMS     (  967): acquireWL(22e93f97): PARTIAL_WAKE_LOCK  *alarm* 0x1 967 1000 WorkSource{1000},
V/AlarmManager(  967): sending alarm PendingIntent{347a4584: PendingIntentRecord{2156016d com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454441612795, Int=0
,D/SmartSyncUtils( 6804): isEpsOn(), nState = 0,
,D/PMS     (  967): releaseWL(22e93f97): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  967): acquireWL(2d5c01a2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6804 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6804): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6804): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6804): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 6804): SettingOnTime = 1454479200000, randomSettingOnTime = 1454478740000
D/SmartSyncScreenOnOffTimeReceiver( 6804): SettingOffTime = 1454457600000, randomSettingOffTime = 1454463671000
,D/SmartSyncScreenOnOffTimeReceiver( 6804): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6804): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6804): bNightModeTurnOffOnce = false
,D/PMS     (  967): releaseWL(2d5c01a2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  967): acquireWL(3df83e33): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null
,I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(3df83e33): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/PMS     (  967): runPSCheck
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  967): Checking...,
D/UsbnetService(  967): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  967): >> updateStatus
D/WifiController(  967): handleMessage: E msg.what=155652
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(141835f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(141835f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/NotificationService(  967): plugged=true pluggin=true
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  967): updateBatteryInfo
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  967): battery changed pluggedType: 2
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/PMS     (  967): runPSCheck
D/WifiController(  967): processMsg: StaEnabledState
D/HtcPowerSaver(  967): Checking...
D/WifiController(  967): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  967): handleMessage: X
I/HtcPowerSaver(  967): >> updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  967): acquireWL(165e4769): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 967 1000 null,
I/BatteryService(  967): n_update end
D/PMS     (  967): releaseWL(165e4769): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  967): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3026): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  967): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  967): BroadcastReceiver::onReceive+
D/PMS     (  967): runPSCheck
D/UsbnetService(  967): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  967): Checking...
D/UsbnetService(  967):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  967): >> updateStatus
D/UsbnetService(  967): BroadcastReceiver::onReceive-
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): handleMessage: E msg.what=155652
D/WifiController(  967): processMsg: DeviceActiveState
D/WifiController(  967): processMsg: StaEnabledState
D/WifiController(  967): processMsg: DefaultState
D/WifiController(  967): handleMessage: X
,I/HtcPowerSaver(  967): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  967): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  967): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
