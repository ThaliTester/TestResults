#### Test 5753124374916c2_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/CheckinService( 4675): Preparing to send checkin request
I/EventLogService( 4675): Accumulating logs since 1454681672527
D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.041837 seconds
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1330): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55a5526680 done in 0.042760 seconds
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  970): [1,454,681,709,257 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2914c0b5 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  970): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  970): 01ABC c2:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 3 now 1454681709259
E/WifiAutoJoinController (  970): newSupplicantResults size=3 known=1 true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  970): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  970): ssid=NG700
E/WifiAutoJoinController (  970): id=0
E/WifiAutoJoinController (  970): mode=station
E/WifiAutoJoinController (  970): pairwise_cipher=CCMP
E/WifiAutoJoinController (  970): group_cipher=CCMP
E/WifiAutoJoinController (  970): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  970): wpa_state=COMPLETED
E/WifiAutoJoinController (  970): ip_address=192.168.1.130
E/WifiAutoJoinController (  970): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  970): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  970): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  970): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  970): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-58,-127) num=(1,0)
E/WifiAutoJoinController (  970): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  970): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-58 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  970): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  970): Done attemptAutoJoin status=0
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
--------- beginning of system
W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/CheckinRequestBuilder( 4675): Checkin reason type: 11 attempt count: 1
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=223 Rx=337
I/ActivityManager(  970): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4675): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1963): Explicit concurrent mark sweep GC freed 8462(417KB) AllocSpace objects, 0(0B) LOS objects, 48% free, 4MB/8MB, paused 1.040ms total 63.239ms
D/Finsky  ( 6381): [642] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6381): [1] 5.onFinished: Installation state replication succeeded.
I/art     (  970): Explicit concurrent mark sweep GC freed 31870(2010KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 17MB/25MB, paused 1.684ms total 148.252ms
E/cutils-trace( 7034): Error opening trace file: Permission denied (13)
I/GLSUser ( 1963): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1963): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1963): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1963): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/CheckinRequestBuilder( 4675): awaiting user notification for token
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
I/ActivityManager(  970): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7052 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/CustomizationManager( 7034): ====startRecUseTime====
D/htc.customization.log.level( 7034):  is 
W/CustomizationLogLevel( 7034): Level value is invalid, use default level 2
W/ResourcesManager( 7052): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7052): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7052): VM with version 2.1.0 has multidex support
I/MultiDex( 7052): install
I/MultiDex( 7052): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7052): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/CustomizationManager( 7034):  Read ACC file spent 0.042 (s)
D/CIDMapFileReader( 7034): Parsing tag item name = HTC__001
D/CIDMapFileReader( 7034): Parsing tag item name = HTC__102
D/CIDMapFileReader( 7034): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7034): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7034): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 7034): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7034): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 7034): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 7034): Parsing tag category name = system
I/CustomizationCIDLoader( 7034): Parsing tag category name = application
I/CustomizationCIDLoader( 7034): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 7034): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7034): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7034): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7034): Parsing tag category name = ACC
I/CustomizationCIDLoader( 7034): add string-array item, value = 42507
I/CustomizationCIDLoader( 7034): add string-array item, value = 21902
I/CustomizationCIDLoader( 7034): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7034): add string-array item, value = 23420
I/CustomizationCIDLoader( 7034): add string-array item, value = 22299
I/CustomizationCIDLoader( 7034): add string-array item, value = 24002
I/CustomizationCIDLoader( 7034): add string-array item, value = 23210
I/CustomizationCIDLoader( 7034): add string-array item, value = 23205
I/CustomizationCIDLoader( 7034): add string-array item, value = 23806
I/CustomizationCIDLoader( 7034): add string-array item, value = 23430
I/CustomizationCIDLoader( 7034): add string-array item, value = 23408
I/CustomizationCIDLoader( 7034): add string-array item, value = 27205
I/CustomizationCIDLoader( 7034): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7034): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7034):  Read CID file spent 0.086 (s)
D/CustomizationManager( 7034):  All configurations done spent 0.086 (s)
W/ActivityThread( 7052): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7052): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2bf8f685: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7052): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1963): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1963): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4675): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/PMS     (  970): acquireHCC(281c8901): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
D/PMS     (  970): acquireHCC(3daad3a6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7034 on display 0
D/WearableService( 6080): callingUid 10024, callindPid: 6080
W/asset   (  970): Copying FileAsset 0x558ba88250 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  970): acquireWL(c47b43d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
I/FeedHostManager( 1625): [onPause]
I/AnimationUtil(  970): isHTCRecent(ThaliTest/Recent screens.)/6
I/FeedProviderManager( 1625): onPause
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4675, uid=10024, userID:0
E/MDM     ( 1798): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/FeedHostManager( 1625): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3825e3c0
I/SocialFeedProvider( 1625): +onPause
I/SocialFeedProvider( 1625): -onPause
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  970): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7077 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  970): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  970): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  970): hiding MENU key
W/asset   ( 7077): Copying FileAsset 0xac590e50 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1625): [trimMemory] 20
D/LocationInitializer( 4675): Restart initialization of location
I/WVCdm   (  399): CdmEngine::OpenSession
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  399): Service_Initialize: starts!
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
D/QSEECOMAPI: (  399): Loaded image: APP id = 8
D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0
D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46b8000
E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46b8000
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  546): got the req here! ret=0
D/DrmLibTime(  546): command id, time_cmd_id = 770
D/DrmLibTime(  546): time_getutcsec starts!
D/DrmLibTime(  546): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  546): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  546): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  546): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  546): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  546): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  546): QSEE Time Listener: Retrieved Android system time: 1454681710
D/DrmLibTime(  546): time_getutcsec returns 0, sec = 1454681710; nsec = 0
D/DrmLibTime(  546): time_getutcsec finished! 
D/DrmLibTime(  546): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  546): before calling ioctl to read the next time_cmd
E/QC-time-services(  453): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xfff00c08
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xab18dd58, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab184f70, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xab05b2e8, idLength=0xf47e46f8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xf47e470e, maximum = 0xf47e470f
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf47e477c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  399): PrepareKeyRequest: nonce=3940537133
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab072f68
D/DrmWidevineDash(  399): message_length=1611, signature=0xab0bb400, signature_length=0xf47e46dc
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/WebViewFactory( 7077): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:1092] from screen [on:0 period:-1312203043] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1312203043] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
I/LibraryLoader( 7077): Time to load native libraries: 10 ms (timestamps 139-149)
I/LibraryLoader( 7077): Expected native library version number "",actual native library version number ""
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=223 Rx=338
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  970): notifying of data activity 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.26 txretriesrate=0.00 rxrate=1.28 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  970):  isHighRSSI       ---> score=61
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -58, 3
V/WebViewChromiumFactoryProvider( 7077): Binding Chromium to main looper Looper (main, tid 1) {1c1e9679}
I/LibraryLoader( 7077): Expected native library version number "",actual native library version number ""
I/chromium( 7077): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/BrowserStartupController( 7077): Initializing chromium process, singleProcess=true
W/art     ( 7077): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7077): ApplicationContext is null in ApplicationStatus
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  399): CdmEngine::CloseSession
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!
D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
W/chromium( 7077): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7077): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7077): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7077): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7077): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7077): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7077): Local Branch: 
I/Adreno-EGL( 7077): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7077): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7077):                  d74aa161a12b9c6fc6332151
E/cutils-trace( 7110): Error opening trace file: Permission denied (13)
I/dex2oat ( 7110): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7110): dex2oat: override thread count:4
D/BluetoothManagerService(  970): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  970): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cc8762e:true
W/System.err(  970): java.lang.Throwable: stack dump
W/System.err(  970): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  970): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 7077): 636035381: getState(). Returning 12
I/dex2oat ( 7110): dex2oat took 54.596ms (threads: 4)
I/Adreno-EGL( 7052): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7052): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7052): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7052): Local Branch: 
I/Adreno-EGL( 7052): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7052): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7052):                  d74aa161a12b9c6fc6332151
W/art     ( 7077): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7077): onDetachedFromWindow called when already detached. Ignoring
I/Adreno-EGL( 7052): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7052): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7052): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7052): Local Branch: 
I/Adreno-EGL( 7052): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7052): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7052):                  d74aa161a12b9c6fc6332151
D/SystemWebViewEngine( 7077): CordovaWebView is running on device made by: HTC
W/art     ( 7077): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7077): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7077): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 7077): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/WVCdm   (  399): CdmEngine::OpenSession
I/WVCdm   (  399): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  399): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  399): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  399): Service_Initialize: starts!
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
E/QSEECOMAPI: (  399): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  399): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  399): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  399): App is not loaded in QSEE
D/QSEECOMAPI: (  399): Loaded image: APP id = 9
D/DrmWidevineDash(  399): Service_Initialize: ends! returns 0
I/InputMethodManager( 7077): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2eb1e97a, mServedView=org.apache.cordova.engine.SystemWebView{253fc52b VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@347c3d88
D/QSAPPSVER(  399): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  399): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  399): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46b8000
E/DrmWidevineDash(  399): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46b8000
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  546): got the req here! ret=0
I/InputMethodManagerService(  970): Disable input method client, pid=1625
D/DrmLibTime(  546): command id, time_cmd_id = 770
D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
D/DrmLibTime(  546): time_getutcsec starts!
I/InputMethodManagerService(  970): Enable input method client, pid=7077
D/DrmLibTime(  546): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  546): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  546): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  546): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  546): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  546): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  546): QSEE Time Listener: Retrieved Android system time: 1454681710
D/DrmLibTime(  546): time_getutcsec returns 0, sec = 1454681710; nsec = 0
D/DrmLibTime(  546): time_getutcsec finished! 
D/DrmLibTime(  546): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  546): before calling ioctl to read the next time_cmd
E/QC-time-services(  453): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/ActivityManager(  970): Displayed com.test.thalitest/.MainActivity: +856ms
D/DrmWidevineDash(  399): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/PMS     (  970): releaseWL(c47b43d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  399): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: starts! SID=0xf48e4928
D/DrmWidevineDash(  399): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  399): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: starts! randomData=0xab18e080, dataLength=8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab184f70, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  399): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  399): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  399): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  399): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: starts! deviceID=0xab05b308, idLength=0xf42646f8
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/XT9_C   ( 1393): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1393): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1393): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1393): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  399): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: starts!, current = 0xf426470e, maximum = 0xf426470f
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): hlos api version =  9
D/DrmWidevineDash(  399): tz api version =  9
D/DrmWidevineDash(  399): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf426477c
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  399): PrepareKeyRequest: nonce=1472431639
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab072f68
D/DrmWidevineDash(  399): message_length=1646, signature=0xab0bb400, signature_length=0xf42646dc
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/BindingManager( 7077): Cannot call determinedVisibility() - never saw a connection for the pid: 7077
D/JsMessageQueue( 7077): Set native->JS mode to OnlineEventsBridgeMode
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  399): CdmEngine::CloseSession
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  399): L3 Terminate.
D/DrmWidevineDash(  399): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  399): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  399): Service_Uninitialize: starts!
D/QSEECOMAPI: (  399): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  399): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  399): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  399): OEMCrypto_Terminate: ends! returns 0
I/CheckinRequestBuilder( 4675): Classify the device as Phone.
D/libc    ( 4675): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4675): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4675): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4675): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4675): [NET] android_getaddrinfo_proxy+
D/libc    ( 4675): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4675): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4675): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4675): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4675): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4675): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4675): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4675): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4675): Sending checkin request (8449 bytes)
D/jxcore_app_log( 7077): JniHelper::setJavaVM(0xab4258f8), pthread_self() = -1401693992
I/chromium( 7077): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  970):  packet count Tx=238 Rx=348
D/WIFI_ICON( 1221): WifiActivity: 3
E/WifiTrafficPoller(  970): notifying of data activity 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/CheckinRequestBuilder( 4675): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  970): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4675): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/GLSUser ( 1963): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
,I/GLSUser ( 1963): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1963): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1963): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4675): awaiting user notification for token
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 1 40
,I/CheckinRequestBuilder( 4675): Classify the device as Phone.,
,I/CheckinTask( 4675): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4675): Checking schedule, now: 1454681711902 next: 1455218543879,
I/CheckinService( 4675): active receiver: disabled
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4675, uid=10024, userID:0
,D/PMS     (  970): releaseHCC(281c8901): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  970): releaseHCC(3daad3a6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/PMS     (  970): releaseWL(28af8c2a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  970): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7152 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/PhoneMonitor( 7152): Register our PhoneStateListener
,V/SetupWizard( 7152): Connected to Gservices successfully,
,D/ChimeraCfgMgr( 4675): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PhoneMonitor( 7152): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,I/Kids    ( 4675): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 7152): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1963): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,W/jxcore-log( 7077): Initializing JXcore engine
,W/jxcore-log( 7077): JXcore engine is ready
,W/jxcore-log( 7077): Starting JXcore engine
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  970):  packet count Tx=239 Rx=351
,W/jxcore-log( 7077): Platform android,
W/jxcore-log( 7077): 
W/jxcore-log( 7077): Process ARCH arm
W/jxcore-log( 7077): 
,I/HtcModeClient( 3434): handler message = 4011,
E/HtcModeClient( 3434): Check connection and retry 12 times.
,I/jxcore-log( 7077): JXcore Cordova bridge is ready!,
I/jxcore-log( 7077): 
,W/jxcore-log( 7077): JXcore engine is started
,I/jxcore-log( 7077): Toggling radios to true,
I/jxcore-log( 7077): 
,D/BluetoothAdapter( 7077): enable(): BT is already enabled..!,
,D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 7
D/WifiManager( 7077): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  970): MONITOR_LOG
D/WifiService(  970): setWifiEnabled: true pid=7077, uid=10366
W/Settings:Agent(  970): name: wifi_on
E/WifiService(  970): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  970): value: 2
I/WifiService(  970): isSprintWifiRestricted(): false
W/Settings:Agent(  970): >> traceCallingStack()
I/WifiService(  970): isMdmWifiRestricted(): false
W/Settings:Agent(  970): Process.myPid(): 970
W/Settings:Agent(  970): Process.myTid(): 1608
W/Settings:Agent(  970): Process.myUid(): 1000
W/Settings:Agent(  970): 
W/Settings:Agent(  970): 
,W/System.err(  970): java.lang.Throwable: stack dump
,W/System.err(  970): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  970): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  970): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  970): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  970): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  970): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  970): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  970): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  970): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  970): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  970): 
W/Settings:Agent(  970): << traceCallingStack(): 27(ms)
D/WifiController(  970): handleMessage: E msg.what=155656
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): handleMessage: X
D/WifiManager( 7077): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  970): handleMessage: E msg.what=131145
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_DISCONNECT 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1330): wlan0: Cancelling scan request,
D/WifiManager( 7077): reconnect: Base Package Name=com.test.thalitest, uid=10366
D/wpa_supplicant( 1330): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1330): TDLS: Tear down peers
D/wpa_supplicant( 1330): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 7077): Radios toggled
I/jxcore-log( 7077): 
I/jxcore-log( 7077): My device name is: HTC-HTC One M8s
I/jxcore-log( 7077): 
,D/wpa_supplicant( 1330): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1330): wlan0: Deauthentication notification
D/wpa_supplicant( 1330): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1330): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1330): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1330): enter disconnect check
I/wpa_supplicant( 1330): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  970): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  970): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  970): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1330): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1330): wlan0: Ignore connection failure indication since interface has been put into disconnected state
,D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  970): acquireWL(2b839ec1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/Tethering(  970): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  970): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  970): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  970): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
,D/wpa_supplicant( 1330): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1330): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1330): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1330): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1330): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a5523f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1330):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1330): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1330): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1330): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1330): EAPOL: SUPP_PAE entering state DISCONNECTED
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/wpa_supplicant( 1330): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1330): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1330): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1330): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1330): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1330): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1330): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1330): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1330): EAPOL: External notification - portEnabled=0
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1330): EAPOL: External notification - portValid=0
D/WifiP2pService(  970): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1330): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1330): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1330): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  970): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: ConnectedState
E/WifiStateMachine(  970): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  970): release()
E/WifiStateMachine(  970): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  970): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  970): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  970): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1330): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1330): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1330): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1330): Power_Mode_Type mode = 0
I/wpa_supplicant( 1330): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1330): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  970): setDhcpActive: false
V/NativeCrypto( 1963): Read error: ssl=0x558b70d340: I/O error during system call, Connection timed out
,D/PMS     (  970): acquireWL(2baf9666): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  970): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  970): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): NetworkAgent != null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/TetherSettings( 6758): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6758): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6758): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6758): Cust_ConnectToPC   : spcsc>false
D/        ( 6758): Cust_ConnectToPC   : IPT>true
D/        ( 6758): Cust_ConnectToPC   : Singel_USB>false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  970):  packet count Tx=239 Rx=352
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  970): notifying of data activity 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NativeCrypto( 1963): SSL shutdown failed: ssl=0x558b70d340: I/O error during system call, Broken pipe
,I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  970): releaseWL(2b839ec1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/Settings( 6758): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  970): autoRoamSetBSSID any key="NG700"WPA_PSK
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
V/NetworkPolicy(  970): updateNotificationsLocked()
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WIFI_ICON( 1221): WifiActivity: 1
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  970): stopDataStallAlarm 
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SAVE_CONFIG'
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/wpa_supplicant( 1330): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 1
,D/wpa_supplicant( 1330): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1330): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  970):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  970): Start Disconnecting Watchdog 1
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131146
E/WifiStateMachine(  970): processMsg: DisconnectingState
E/WifiStateMachine(  970):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/SmartNS_Utility( 6758): hasRemovableStorageSlot: true
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1330): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1330): wlan0: Selecting BSS from priority group 626
D/wpa_supplicant( 1330): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-52 wps
D/wpa_supplicant( 1330): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1330): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1330): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
D/wpa_supplicant( 1330): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1330): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1330): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1330):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1330): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/wpa_supplicant( 1330): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x55a5525c00  current_ssid=0x0
D/wpa_supplicant( 1330): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1330): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1330): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/ConnectivityService(  970): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1330): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1330): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 1330): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1330): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1330): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1330): wlan0: Add radio work 'connect'@0x55a5526680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'connect'@0x55a5526680 after 0.000265 second wait
I/wpa_supplicant( 1330): check if in concurrent case
I/wpa_supplicant( 1330): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/SmartNS_Utility( 6758): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/WifiMonitor(  970): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=33 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/SmartNS_NSReceiver( 6758): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
,E/WifiStateMachine(  970): handleMessage: E msg.what=147460
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): processMsg: DisconnectingState
D/wpa_supplicant( 1330): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1330): wlan0: Cancelling scan request
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1330): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1330): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1330): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1330): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 1330): wlan0: Automatic auth_alg selection: 0x1
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1330): RSN: PMKSA cache search - network_ctx=0x55a5525c00 try_opportunistic=0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1330): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1330): wlan0: RSN: using IEEE 802.11i/D9.0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1330): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1330): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1330): wlan0: WPA: clearing AP WPA IE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1330): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): wlan0: WPA: using GTK CCMP
,D/wpa_supplicant( 1330): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1330): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1330): wlan0: WPA: not using MGMT group cipher
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Forcing reevaluation
D/wpa_supplicant( 1330): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): wlan0: State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1330): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1330): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1330): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1330): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
E/WifiStateMachine(  970):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=102868
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/wpa_supplicant( 1330): nl80211: Unsubscribe mgmt frames handle 0x888888dd2ddad989 (mode change)
D/wpa_supplicant( 1330): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a5525100
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=0104
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=040a
E/WifiStateMachine(  970):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=102869
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=040b
E/WifiStateMachine(  970): ConnectModeState: Network connection lost 
E/WifiStateMachine(  970): transitionTo: destState=DisconnectedState
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=040c
,E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=040d
D/PMS     (  970): releaseWL(2baf9666): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,E/WifiStateMachine(  970): invokeExitMethods: DisconnectingState
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=090a
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  970): invokeEnterMethods: DisconnectedState
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=090b
E/WifiStateMachine(  970): DisconnectedState call setCountryCode()
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=090c
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=090d
E/WifiStateMachine(  970):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=0409506f9a09
,D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=7f506f9a09
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=0801
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=040e
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=06
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=0a07
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=0a11
D/wpa_supplicant( 1330): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a5525100 match=0a1a
D/wpa_supplicant( 1330): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1330):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330):   * freq=2412
D/wpa_supplicant( 1330):   * freq_hint=2412
D/wpa_supplicant( 1330):   * SSID - hexdump(len=5): 4e 47 37 30 30
,D/wpa_supplicant( 1330):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1330):   * WPA Versions 0x2
D/wpa_supplicant( 1330):   * pairwise=0xfac04
D/wpa_supplicant( 1330):   * group=0xfac04
D/wpa_supplicant( 1330):   * akm=0xfac02
D/wpa_supplicant( 1330):   * Auth Type 0
D/wpa_supplicant( 1330): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55a5525c3a
D/wpa_supplicant( 1330): nl80211: Connect request send successfully
D/wpa_supplicant( 1330): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1330): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1330): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1330): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY'
,D/wpa_supplicant( 1330): Ongoing scan action - reject new request
E/WifiStateMachine(  970): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=102880  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=102881  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
,D/WifiNetworkAgent(  970): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  970): handleMessage: E msg.what=131213
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=102887
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=102888
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=102888
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=102889
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
,E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=102889  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=102895  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  970): handleMessage: X
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ContextImpl( 6758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 6758): setISNotification
D/SmartNS_Utility( 6758): usb_cable_connect = 1
D/SmartNS_Utility( 6758): usb_denied = 0
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
I/SmartNS_PSService( 6758): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 6758): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
,D/SmartNS_Utility( 6758): usb_cable_connect = 1
D/SmartNS_Utility( 6758): usb_denied = 0
I/SmartNS_PSService( 6758): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0,
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1221): reapply : com.android.settings 1 36
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Disconnected - quitting
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  970): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  970): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  970): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkManagementService(  970): Removing idletimer
D/SmartNS_NSReceiver( 6758): Tethered state change:false isNSOpening:false
D/PMS     (  970): acquireWL(17e62254): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 970 1000 null
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  970): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  970): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/SecurityController( 1221): onLost 100
E/ConnectivityService(  970): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/PMS     (  970): acquireWL(2c6a65fd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/Tethering(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
,E/ConnectivityService(  970): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
I/RemoteViews( 1221): reapply : com.android.settings 2 36
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateIfacesLocked()
V/NetworkPolicy(  970): updateNotificationsLocked()
,D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
,D/DATA_ICON( 1221): dataConnected: false/false
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WISPrService( 6758): >>>>>WISPrService start isConnected = true<<<<<
,I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=7183 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  970): New client listening to asynchronous messages
E/WifiTrafficPoller(  970): ADD_CLIENT: 8
,D/PMS     (  970): releaseWL(2c6a65fd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
E/WifiStateMachine(  970): handleMessage: E msg.what=131131
V/NetworkPolicy(  970): updateNotificationsLocked()
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): handleMessage: X
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,W/WISPrService( 6758): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/WISPrService( 6758): trigger connection
D/WISPrService( 6758): continue
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/wpa_supplicant( 1330): Wireless event: cmd=0x8c02 len=271
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1330): WEXT: Custom wireless event: 'BEACONIEs='
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1330): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1330): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1330): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/PMS     (  970): acquireWL(283367ec): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/UsbDeviceManager(  970): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1330): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1330): nl80211: Connect event
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1330): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1330): wlan0: Association info event
D/wpa_supplicant( 1330): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): wlan0: freq=2412 MHz
D/wpa_supplicant( 1330): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1330): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1330): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1330): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1330): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1330): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1330): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1330): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1330): wlan0: WPA: Clear old PTK
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1330): TDLS: Remove peers on association
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1330): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1330): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1330): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1330): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1330): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1330): EAPOL: enable timer tick
D/wpa_supplicant( 1330): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1330): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1330): wlan0: Cancelling scan request
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChang,e(): SSIDNG700
I/wpa_supplicant( 1330): htc_wext_set_keepalive +
I/wpa_supplicant( 1330): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1330): getPrivFuncNum +	
I/wpa_supplicant( 1330): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1330): htc_wext_set_keepalive - ret = 0
D/wpa_supplicant( 1330): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): wlan0: Setting authentication timeout: 10 sec 0 usec
D/WifiMonitor(  970): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
D/wpa_supplicant( 1330): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1330): wlan0:   EAPOL-Key type=2
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
D/WifiMonitor(  970): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1330): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/WifiMonitor(  970): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1330): wlan0:   key_length=16 key_data_length=0
D/HTCRequest(  970): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1330):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1330):   key_nonce - hexdump(len=32): ea c8 31 87 e8 bb 0b 72 5f c4 7b 4b 0c d3 13 69 ac ee 84 0b 5a 97 71 bf d5 62 ef f5 dd 52 0e c4
D/wpa_supplicant( 1330):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1330):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1330):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1330):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1330): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1330): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1330): RSN: msg 1/4 key data - hexdump(len=0):
D/HTCRequest(  970): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=102984  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info0x
,E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HTCRequest(  970): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  970): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  970): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  970): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  970): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
D/Tethering(  970): interfaceLinkStateChanged wlan0, false
D/Tethering(  970): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=102986  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1330): WPA: Renewed SNonce - hexdump(len=32): e2 72 83 21 0e 8e 47 f1 74 10 31 0c 2f 50 16 89 ab 0b 56 06 0a 64 54 04 66 36 1d 99 83 17 65 8e
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1330): WPA: Nonce1 - hexdump(len=32): e2 72 83 21 0e 8e 47 f1 74 10 31 0c 2f 50 16 89 ab 0b 56 06 0a 64 54 04 66 36 1d 99 83 17 65 8e
D/wpa_supplicant( 1330): WPA: Nonce2 - hexdump(len=32): ea c8 31 87 e8 bb 0b 72 5f c4 7b 4b 0c d3 13 69 ac ee 84 0b 5a 97 71 bf d5 62 ef f5 dd 52 0e c4
D/wpa_supplicant( 1330): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1330): WPA: PTK - hexdump(len=48): [REMOVED]
,D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/wpa_supplicant( 1330): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1330): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1330): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1330): WPA: Derived Key MIC - hexdump(len=16): 45 66 eb 39 ee ab e7 5a 89 08 6a 39 63 74 39 95
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/Tethering(  970): interfaceStatusChanged wlan0, true
,E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147500
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  970): Enter handleAssociatedWithEvent
D/WifiStateMachine(  970): Associated
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  970): TetherInterfaceSM: wlan0: enter InitialState
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  970): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateMachine(  970): Exit handleAssociatedWithEvent
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
D/Tethering(  970): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=102990  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  970): setDetailed state send new extra info"NG700"
,E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WISPrService( 6758): start DataConnection
D/libc    ( 6758): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6758): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6758): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6758): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6758): [NET] android_getaddrinfo_proxy+
D/libc    ( 6758): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6758): [NET] android_getaddrinfo_proxy-, NODATA
,D/wpa_supplicant( 1330): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1330): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1330): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1330): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1330):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1330):   key_nonce - hexdump(len=32): ea c8 31 87 e8 bb 0b 72 5f c4 7b 4b 0c d3 13 69 ac ee 84 0b 5a 97 71 bf d5 62 ef f5 dd 52 0e c4
D/wpa_supplicant( 1330):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1330):   key_rsc - hexdump(len=8): 66 18 00 00 00 00 00 00
D/wpa_supplicant( 1330):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1330):   key_mic - hexdump(len=16): 26 09 17 74 a3 f2 de dc 8b af 10 0a d6 a8 be 5e
D/wpa_supplicant( 1330): RSN: encrypted key data - hexdump(len=56): d9 ef 7c be 97 27 bf e1 d3 37 23 46 43 08 4f f3 94 76 47 26 8a 72 fb cf e8 5d e0 e8 d2 5b ea cf ...
D/wpa_supplicant( 1330): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1330): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1330): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1330): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 8a ee ...
D/wpa_supplicant( 1330): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1330): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1330): wlan0: WPA: Sending EAPOL-Key 4/4
D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1330): WPA: KCK - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 1330): WPA: Derived Key MIC - hexdump(len=16): 19 b2 19 6b 08 10 13 4c e1 b3 8f ec 6f 13 57 15
D/wpa_supplicant( 1330): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1330): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55a5526390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1330): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/PMS     (  970): releaseWL(283367ec): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  970): NetworkAgent == null
D/wpa_supplicant( 1330): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1330):    addr=c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=102996  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  970): handleMessage: X
D/wpa_supplicant( 1330): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1330): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
D/wpa_supplicant( 1330): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
V/NetworkPolicy(  970): updateNotificationsLocked()
D/wpa_supplicant( 1330): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1330): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1330): WPA: RSC - hexdump(len=6): 66 18 00 00 00 00
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1330): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x556b024e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1330): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1330): nl80211: KEY_SEQ - hexdump(len=6): 66 18 00 00 00 00
D/wpa_supplicant( 1330):    broadcast key
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1330): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1330): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1330): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1330): wlan0: Radio work 'connect'@0x55a5526680 done in 0.136742 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1330): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  970): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  970): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=40 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  ,970): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  970): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1330): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1330): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1330): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  970): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=42 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  970): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1330): set send_ind_to_ndc = 0
I/wpa_supplicant( 1330): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1330): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1330): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1330): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1330): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1330): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1330): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1330): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1330): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1330): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  970): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1330): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1330): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1330): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  970): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  970): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/wpa_supplicant( 1330): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/Tethering(  970): interfaceLinkStateChanged wlan0, true
D/Tethering(  970): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): handleMessage: E msg.what=131101
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  970): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  970): handleMessage: X
D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=103012  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  970): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=103013  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147459
E/WifiStateMachine(  970): processMsg: DisconnectedState
E/WifiStateMachine(  970):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=103014
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=103015
E/WifiStateMachine(  970): Network connection established
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WifiStateMachine(  970): fetchFrequency(), freq = 2412
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): transitionTo: destState=ObtainingIpState
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  970): invokeExitMethods: DisconnectedState
,E/WifiStateMachine(  970): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 20
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  970): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  970): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  970): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  970): NetworkAgent == null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800,
,D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 21
,D/ConnectivityService(  970): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  970): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  970): Got NetworkAgent Messenger
E/WifiStateMachine(  970): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  970): NetworkAgent connected
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1330): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1330): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1330): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  970): invokeEnterMethods: ObtainingIpState
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  970): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  970): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  970): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  970): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  970): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1330): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1330): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1330): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1330): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1330): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): Start Dhcp Watchdog 2
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=147462
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970): processMsg: ObtainingIpState
,E/WifiStateMachine(  970):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=103044  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/WifiStateMachine(  970): processMsg: L2ConnectedState
D/libc    ( 6758): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6758): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  970):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=103045  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=103045  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ObtainingIpState
,D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2885] from screen [on:0 period:-1312200142] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1312200141] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WISPrService( 6758): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  970): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
I/wpa_supplicant( 1330): environment dirty rate=0 [2][0][0]
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
,E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=119.50 txretriesrate=0.00 rxrate=176.00 userTriggerdPenalty0
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970):  good link -> stuck count =0
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): calculateWifiScore() report new score 60
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -57, 3
D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970): handleMessage: X
D/FlexNetS( 6997): updateSvcAllowedInSettings:false
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ObtainingIpState
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  970):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
D/WISPrService( 6758): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
D/WISPrService( 6758): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=196612
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): processMsg: ObtainingIpState
,E/WifiStateMachine(  970):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=239,0,0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=239,0,0
D/WifiStateMachine(  970): handlePreDhcpSetup Held wake lock during DHCP
D/WifiDataStallTracker(  970): setDhcpActive: true
D/PMS     (  970): acquireWL(946dd33): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 970 1000 null
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  970): handlePreDhcpSetup mBluetoothConnectionActive: false
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1330): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  970): do suspend false
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1330): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1330): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1330): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1330): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1330): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1330): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): Unexpected BatchedScanResults :null
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1330): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  970): noteBatchedScanstop()
E/WifiStateMachine(  970): handleMessage: X
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2baa6212 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  970): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2baa6212 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  970): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=7211 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/WifiService(  970): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false,
,D/TetherSettings( 6758): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
,W/ContextImpl( 6758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 6758): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6758): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6758): Cust_ConnectToPC   : spcsc>false
D/        ( 6758): Cust_ConnectToPC   : IPT>true
D/        ( 6758): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 6758): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 6758): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 6758): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6758): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
I/SmartNS_Utility( 6758): setISNotification
D/SmartNS_Utility( 6758): usb_cable_connect = 1
D/SmartNS_Utility( 6758): usb_denied = 0
I/SmartNS_PSService( 6758): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 6758): usb_cable_connect = 1
D/SmartNS_Utility( 6758): usb_denied = 0
I/SmartNS_PSService( 6758): usb notificaiton:true
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1221): reapply : com.android.settings 0 36
E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ObtainingIpState
D/SmartNS_NSReceiver( 6758): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  970):  ObtainingIpState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=119.5, 0.0, 0.0  rx=176.0 bcn=0 [on:0 tx:0 rx:0 period:109] from screen [on:0 period:-1312200025] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 22 num clients 8
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=119.5, 0.0, 0.0  rx=176.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1312200024] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): handleMessage: X
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/FlexNetS( 6997): updateSvcAllowedInSettings:false
I/RemoteViews( 1221): reapply : com.android.settings 3 36
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 7211): [b27.2.]  listen tmrbb8
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false
,D/FlexNetS( 6997): updateSvcAllowedInSettings:false,
E/dhcpcd  ( 7236): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 7236): version 5.5.6 starting
E/dhcpcd  ( 7236): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 7236): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 7236): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 7236): wlan0: rebinding lease of 192.168.1.130
,I/dhcpcd  ( 7236): wlan0: sending REQUEST (xid 0xdf55879b), next in 1.85 seconds
,D/MdProvGlob( 7183): remove item 101 (p2d27in257) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 7211): [b27.2.] summary 118:p2 ignore
,D/Process (  970): killProcessQuiet, pid=5999,
I/ActivityManager(  970): Killing 5999:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5999
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 22 num clients 8,
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 2,
,D/wpa_supplicant( 1330): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1330): EAPOL: disable timer tick
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): handleMessage: E msg.what=131212
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
,E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  970): handleMessage: X
,I/dhcpcd  ( 7236): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,I/ActivityManager(  970): Killing 6821:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
D/Process (  970): killProcessQuiet, pid=6821
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 7236): wlan0: leased 192.168.1.130 for 86400 seconds,
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
I/dhcpcd  ( 7236): autoip env[11]:autoip=DISABLE
,E/WifiStateMachine(  970): handleMessage: E msg.what=131212
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  970): handleMessage: X
,I/ActivityManager(  970): Recipient 6821
,I/dhcpcd  ( 7236): bind_interface: daemonise,
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  970): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  970): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  970): handleMessage: E msg.what=196613
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  970): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1330): Power_Mode_Type mode = 0
I/wpa_supplicant( 1330): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1330): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  970): setDhcpActive: false
E/WifiStateMachine(  970): handlePostDhcpSetup release wake lock during DHCP
D/PMS     (  970): releaseWL(946dd33): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  970): WifiStateMachine DHCP successful
E/WifiStateMachine(  970): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  970): link address 192.168.1.130/24
E/WifiStateMachine(  970): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  970): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  970): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  970): gateway: /192.168.1.1
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1330): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1330): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131210
E/WifiStateMachine(  970): processMsg: ObtainingIpState
E/WifiStateMachine(  970):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1330): environment dirty rate=0 [4][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1330): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=44 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -56, 3
E/WifiStateMachine(  970): NetworkAgent != null
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  970): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  970): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 22
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiTrafficPoller(  970):  packet count Tx=242 Rx=353
D/ConnectivityService(  970): Adding iface wlan0 to network 101
E/WifiTrafficPoller(  970): notifying of data activity 3
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/ActivityManager(  970): Killing 6871:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=6871
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/HtcWifiWanDetect(  970): WAN detection
D/WifiDataStallTracker(  970): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  970): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 2
D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/WIFI_ICON( 1221): WifiActivity: 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/ConnectivityService(  970): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  970): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  970): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
,D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  970): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/ActivityManager(  970): Recipient 6871,
,D/Process (  970): killProcessQuiet, pid=6847
I/ActivityManager(  970): Killing 6847:com.htc.cs.dm/u0a99 (adj 15): empty #18
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  970): Recipient 6847
,E/WifiStateMachine(  970): transitionTo: destState=ConnectedState,
E/WifiStateMachine(  970): handleMessage: new destination call exit/enter
E/WifiStateMachine(  970): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  970): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  970): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  970): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  970): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  970): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  970): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  970): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Connected
D/ConnectivityService(  970): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  970): currentScore = 0, newScore = 20
D/ConnectivityService(  970):    accepting network in place of null
D/ConnectivityService(  970): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
E/WifiStateMachine(  970): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 23
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
E/WifiStateMachine(  970): handleMessage: X
E/WifiTrafficPoller(  970):  packet count Tx=242 Rx=353
E/WifiTrafficPoller(  970): notifying of data activity 0
D/WIFI    (  970): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI_ICON( 1221): WifiActivity: 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WISPrService( 6758): >>>>>WISPrService start isConnected = true<<<<<
D/CSLegacyTypeTracker(  970): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
V/NetworkPolicy(  970): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  970): handleMessage: E msg.what=131131
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  970): processMsg: L2ConnectedState
D/ConnectivityService(  970): sendGeneralBroadcastDelayed, restrictEnable=false
E/WifiStateMachine(  970):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  970): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/ConnectivityService(  970): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
E/WifiStateMachine(  970):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970): handleMessage: X
,D/Tethering(  970): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  970): acquireWL(3e0c9825): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
D/Tethering(  970): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  970): Validated
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
V/NetworkPolicy(  970): ensureActiveMobilePolicyLocked()
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1221): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkPolicy(  970): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
V/NetworkPolicy(  970): updateIfacesLocked()
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  970): updateNotificationsLocked()
D/WISPrService( 6758): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  970): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
,D/usbnet  (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/usbnet  (  970):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  970): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/usbnet  (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/DATA_ICON( 1221): dataConnected: false/false
D/WIFI    (  970):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI    (  970): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  970):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  970): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  970):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  970): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1221): CM callback handler got msg 524290
D/DATA_ICON( 1221): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,I/SecurityController( 1221): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/DATA_ICON( 1221): dataConnected: false/false
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  970): releaseWL(3e0c9825): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1221): receive.wifiConnect:true wifiAPname:NG700 elapse:0
V/NetworkPolicy(  970): updateNetworkEnabledLocked()
,V/NetworkPolicy(  970): updateNotificationsLocked()
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  970): acquireWL(13563dfa): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null,
D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  970): acquireWL(2bf6bfab): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
D/GpsLocationProvider(  970): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  970): releaseWL(2bf6bfab): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ConnectivityHelper( 1625): [onReceive] WIFI(1): CONNECTED
D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7277 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=119.5, 0.0, 0.0  rx=176.0 bcn=0 [on:0 tx:0 rx:0 period:2890] from screen [on:0 period:-1312197133] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=119.5, 0.0, 0.0  rx=176.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1312197132] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0],
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  970): BroadcastRSSIForIMS, newrssi =-57 , oldRssi= -200
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -57, 3
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=61.25 txretriesrate=0.00 rxrate=89.00 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -57, 3
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,I/art     (  970): Explicit concurrent mark sweep GC freed 55921(2MB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 17MB/25MB, paused 1.600ms total 150.847ms,
,E/GpsLocationProvider(  970): No APN found to select.
,D/PMS     (  970): releaseWL(13563dfa): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 7211): [acd.1.]  listen tmrbb8
,D/MdScDataSum( 7211): [acd.1.] summary 118:p1 ignore,
,I/MusicStore( 7277): Database version: 120,
,D/VoldConnector(  970): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 7277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  970): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 7277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  970): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
W/ContextImpl( 7277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 7277): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7277): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7277): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 7277): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7277): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1dd14c7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7277): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7277): GMSCore installation verified
,I/ConfigStore( 7277): Config Database version: 1,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=7277, uid=10159, userID:0
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: ,
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,D/MediaRouterService(  970): Client com.google.android.music (pid 7277): Registered,
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
,D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
,I/MediaRouter( 7277): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 7277): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 7277): type=WIFI subType= reason=null isConnected=true
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=242 Rx=354
D/WIFI_ICON( 1221): WifiActivity: 1
E/WifiTrafficPoller(  970): notifying of data activity 1
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/NetworkMonitor( 7277): type=WIFI subType= reason=null isConnected=true,
,D/PMS     (  970): releaseWL(17e62254): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  970): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=7277, uid=10159, userID:0
,D/AutoSetting( 1530): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 7152): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7152): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1530): service - onCreate()
,I/GHttpClientFactory( 7277): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7277): Using platform SSLCertificateSocketFactory
,D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1530): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1530): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1530): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1530): service - handleMessage() setting current location null
,D/LocationManagerService(  970): request 12354510 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  970): provider request: passive ProviderRequest[ON interval=0],
,D/ChimeraCfgMgr( 4675): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4675): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  970): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7320 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 6701): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6701): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6701): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6701): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6701): [NET] android_getaddrinfo_proxy+
D/libc    ( 6701): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6701): [NET] android_getaddrinfo_proxy-, success
,I/Babel   ( 6701): connection state changed from UNKNOWN to CONNECTED
,D/Process (  970): killProcessQuiet, pid=6731,
I/ActivityManager(  970): Killing 6731:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6731
,D/VoldConnector(  970): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 7320): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  970): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7320): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7320): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 7320):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7320):   adb logcat -s GAv4
,D/VoldConnector(  970): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 7320): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  970): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7320): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7320): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7320): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7320): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 7320): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7320): [apache-http] Connection GC has been deprecated!,
,I/HtcModeClient( 3434): handler message = 4011,
E/HtcModeClient( 3434): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3434): Don't start project servcice,
,D/HtcModeClient( 3434): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3434): connectState: CONNECTION_READY = false
D/SilentMusic( 3434): call stop
D/HtcModeClient( 3434): close connection
W/HtcModeClient( 3434): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3434): read the terminate packet, so break
,I/WebViewFactory( 7320): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 7320): Time to load native libraries: 1 ms (timestamps 7365-7366),
I/LibraryLoader( 7320): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7320): Binding Chromium to main looper Looper (main, tid 1) {23005294},
,I/LibraryLoader( 7320): Expected native library version number "",actual native library version number "",
,I/chromium( 7320): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7320): Initializing chromium process, singleProcess=true,
,W/art     ( 7320): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 7320): ApplicationContext is null in ApplicationStatus,
,W/chromium( 7320): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 7320): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 7320): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7320): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7320): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7320): Build Date: 03/09/15 Mon,
I/Adreno-EGL( 7320): Local Branch: 
I/Adreno-EGL( 7320): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7320): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7320):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 7320): Requires BLUETOOTH permission,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8
E/WifiTrafficPoller(  970):  packet count Tx=247 Rx=358
E/WifiTrafficPoller(  970): notifying of data activity 3
D/WIFI_ICON( 1221): WifiActivity: 3
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/NSApplication( 7320): Starting up...
,I/ActivityManager(  970): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7380 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  970): killProcessQuiet, pid=6923,
I/ActivityManager(  970): Killing 6923:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  406): Explicit concurrent mark sweep GC freed 8632(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 167us total 19.191ms,
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 132us total 15.507ms
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 131us total 15.991ms
,I/ActivityManager(  970): Recipient 6923,
,D/Process (  970): killProcessQuiet, pid=3434
I/ActivityManager(  970): Killing 3434:com.htc.autobot/u0a47 (adj 15): empty #18
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131168,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  970): handleMessage: X
,I/ActivityManager(  970): Recipient 3434,
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/jxcore-log( 7077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 7077): 
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/HtcWifiWanDetect(  970): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
,D/Process (  970): killProcessQuiet, pid=6294,
I/ActivityManager(  970): Killing 6294:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,I/ActivityManager(  970): Recipient 6294,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=248 Rx=359
,D/ConnectivityService(  970): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
D/GpsLocationProvider(  970): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  970): acquireWL(1399c6c5): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/GpsLocationProvider(  970): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/AlarmManager(  970): [AlarmQueuing] connectivity wifi: true
,I/ConnectivityHelper( 1625): [onReceive] WIFI(1): CONNECTED
I/NetworkMonitor( 7277): type=WIFI subType= reason=null isConnected=true
,D/htcCheckinService(  970): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,E/GpsLocationProvider(  970): No APN found to select.
,V/MusicLeanback( 7277): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PMS     (  970): releaseWL(1399c6c5): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  970): acquireWL(322b1f4b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,D/PMS     (  970): releaseWL(322b1f4b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1530): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 7152): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7152): onReceive CONNECTIVITY_CHANGE networkType=1
D/MdScPhnSt( 7211): [a83.1.]  listen tmrbb8
D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1530): Util - check NLP state, Allowned:false, Enabled:false,
D/AutoSetting( 1530): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1530): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1530): service - handleMessage() setting current location null
,I/art     ( 4047): Explicit concurrent mark sweep GC freed 4991(257KB) AllocSpace objects, 0(0B) LOS objects, 57% free, 1508KB/3MB, paused 302us total 34.673ms
,D/MdScDataSum( 7211): [a83.1.] summary 118:p1 ignore
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4675, uid=10024, userID:0
,D/ChimeraCfgMgr( 4675): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4675): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
,I/jxcore-log( 7077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 7077): 
,I/jxcore-log( 7077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 7077): 
,I/jxcore-log( 7077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 7077): 
,I/jxcore-log( 7077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7077): 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState,
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=61.2, 0.0, 0.0  rx=89.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1312194113] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=61.2, 0.0, 0.0  rx=89.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1312194112] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=20 [10][2][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
,D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -57, 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=35.12 txretriesrate=0.00 rxrate=47.50 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
E/WifiStateMachine(  970): handleMessage: X
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -57, 3
,D/PMS     (  970): acquireWL(18315072): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6701 10112 null
,W/SystemReader(  970): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1739): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1625): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1625): Deferring update until onResume
D/Launcher( 1625): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1739): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  970): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  970): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7419 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/PhoneApp( 1569): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,D/AccTypeManager( 1739): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,D/PMS     (  970): releaseWL(18315072): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6701): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ExternalAccountType( 1739): Unsupported attribute readOnly
,W/PackageManager(  970): Unable to load service info ResolveInfo{efb3bf7 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  970): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  970): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  970): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  970): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  970): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  970): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1798): DISABLE
,I/GCoreNlp( 1798): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  970): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PMS     (  970): acquireWL(382acfd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1798 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(382acfd): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  970): applying state to connected service
,D/LocationProviderProxy(  970): applying state to connected service
D/PMS     (  970): acquireWL(2e91f73e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1798 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(56f599f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1798 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2e91f73e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): releaseWL(56f599f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationManagerService(  970): getProviders()=[passive]
,I/ActivityManager(  970): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7448 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/[PluginManager]RegisterService( 1530): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1530): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4675): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4675): Null package name or gms related package.  Ignoreing.
,D/PMS     (  970): acquireWL(1b5e7f25): PARTIAL_WAKE_LOCK  Icing 0x1 4675 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(2d9798fa): PARTIAL_WAKE_LOCK  AsyncService 0x1 6787 10167 null
,I/Icing   ( 4675): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  970): releaseWL(2d9798fa): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  970): acquireWL(3b443908): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6787 10167 null
,D/PMS     (  970): releaseWL(3b443908): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/ActivityManager(  970): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=7475 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  970): acquireWL(299ce8a1): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10076}
V/AlarmManager(  970): sending alarm PendingIntent{14364ac6: PendingIntentRecord{10a5a87 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454681719687, Int=60000
D/PMS     (  970): releaseWL(299ce8a1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/PMS     (  970): releaseWL(1b5e7f25): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  970):  packet count Tx=251 Rx=360
,I/UpdateIcingCorporaServi( 7419): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/SMSBackup( 7475): SMSBackupAgentService started,
D/SMSBackup( 7475): Checking restore status
,D/SMSBackup( 7475): Restore complete
,D/SMSBackup( 7475): cancelCheckAlarm
,D/SMSBackup( 7475): SMSBackupAgentService completed: completed in 0.0 seconds
,I/UpdateIcingCorporaServi( 7419): UpdateCorporaTask done [took 114 ms] updated apps [took 114 ms] 
,D/Process (  970): killProcessQuiet, pid=5801,
I/ActivityManager(  970): Killing 5801:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  970): Explicit concurrent mark sweep GC freed 27312(1470KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 1.450ms total 146.147ms
,I/ActivityManager(  970): Recipient 5801
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=224 rxSum=196} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  970): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/PMS     (  970): acquireWL(31bc4d52): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024}
V/AlarmManager(  970): sending alarm PendingIntent{2c281823: PendingIntentRecord{127f2120 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=110236, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{2bf1f122: PendingIntentRecord{fc837b3 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454681715910, Int=20000
,D/PMS     (  970): acquireWL(1af90ad9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  970): WiFiStateMachine SCAN ALARM,
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
E/WifiStateMachine(  970): handleMessage: E msg.what=131143
D/PMS     (  970): releaseWL(31bc4d52): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:49 rssi=-57 f=2412 sc=60 link=72 tx=35.1, 0.0, 0.0  rx=47.5 list=2412 [on:0 tx:0 rx:0 period:1157] from screen [on:0 period:-1312192946]
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:49 rssi=-57 f=2412 sc=60 link=72 tx=35.1, 0.0, 0.0  rx=47.5 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1312192945]
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=35.12 rxSuccessRate=47.50 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-57
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN with age=29063 interval=40000 maxinterval=300000
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  970): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  970): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  970): has c0:ff:d4:d3:aa:48 freq=2412 age=1162 ?=true
E/WifiStateMachine(  970): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
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
,D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
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
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55a5526680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55a5526680 after 0.000038 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
,D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000100 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  970): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970): [1,454,681,720,402 ms] noteScanstart no scan source
E/WifiMonitor(  970): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  970): handleMessage: X
D/libc    ( 1963): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1963): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1963): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1963): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1963): [NET] android_getaddrinfo_proxy+
D/libc    ( 1963): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.080299 seconds
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
D/wpa_supplicant( 1330): BSS: last_scan_res_used=2/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55a5526680 done in 0.081259 seconds
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  970): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  970): handleMessage: E msg.what=147461
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: ConnectModeState
,E/WifiStateMachine(  970):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
,E/WifiStateMachine(  970):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  970): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
,E/WifiStateMachine(  970): [1,454,681,720,486 ms] noteScanEnd no scan source
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  970): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2914c0b5 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  970): NG7005g c0:ff:d4:d3:aa:4a rssi=-52 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  970): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  970): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  970): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  970):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  970): ageScanResultsOut delay 40000 size 3 now 1454681720488
E/WifiAutoJoinController (  970): newSupplicantResults size=3 known=1 true
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  970): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  970): ssid=NG700
E/WifiAutoJoinController (  970): id=0
E/WifiAutoJoinController (  970): mode=station
E/WifiAutoJoinController (  970): pairwise_cipher=CCMP
E/WifiAutoJoinController (  970): group_cipher=CCMP
E/WifiAutoJoinController (  970): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  970): wpa_state=COMPLETED
E/WifiAutoJoinController (  970): ip_address=192.168.1.130
E/WifiAutoJoinController (  970): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  970): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  970): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  970): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  970): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-57,-127) num=(1,0)
E/WifiAutoJoinController (  970): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  970): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-57 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  970): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  970): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  970): Done attemptAutoJoin status=0
E/WifiConfigStore(  970):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  970): handleMessage: X
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1963): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1963): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1963): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1963): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1963): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  970): acquireWL(1a2dec9e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1963 10024 WorkSource{10024 com.google.android.gms},
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=259 Rx=368
D/GCM     ( 1963): Connected
,D/PMS     (  970): releaseWL(1af90ad9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1a2dec9e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(3da137f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(29052f4c): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1963 10024 WorkSource{10024 com.google.android.gms},
,I/GCM     ( 4675): Message from null null
E/GCM     ( 4675): Dropping message from null
,D/PMS     (  970): releaseWL(29052f4c): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms},
,D/GCM     ( 1963): Message class com.google.f.a.a.p,
,D/PMS     (  970): releaseWL(3da137f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1625): loadItems() com.htc.launcher.pageview.WidgetManager@227ef5be +
I/Prism.WidgetManager( 1625): onLoadItems() +
,W/ResourcesManager( 1625): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 1625): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1625): Copying FileAsset 0x558ba977a0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1625): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1625): onLoadItems() -
I/Prism.ItemManager( 1625): loadItems() com.htc.launcher.pageview.WidgetManager@227ef5be -
,D/PhoneApp( 1569): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1569): -- N1 =0
,D/PhoneApp( 1569): -- N2 =0
,D/PhoneApp( 1569): -- N3 =0
,D/PMS     (  970): acquireWL(b8834aa): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7277 10159 null,
,I/PackageManager(  970):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7277, uid=10159, userID:0,
,D/PMS     (  970): releaseWL(b8834aa): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 7277): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7277): Stop autocaching.
,I/art     ( 1963): Explicit concurrent mark sweep GC freed 11729(654KB) AllocSpace objects, 7(460KB) LOS objects, 49% free, 4MB/8MB, paused 694us total 38.462ms,
,D/WearableService( 6080): callingUid 10024, callindPid: 6080,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=260 Rx=369
,E/GmsUtils( 7277): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 7277): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=35.1, 0.0, 0.0  rx=47.5 bcn=0 [on:0 tx:0 rx:0 period:1840] from screen [on:0 period:-1312191102] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=35.1, 0.0, 0.0  rx=47.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1312191100] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970):  get link layer stats 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [10][0][0],
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  970): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=22.56 txretriesrate=0.00 rxrate=28.75 userTriggerdPenalty0
E/WifiStateMachine(  970):  good link -> stuck count =0
E/WifiStateMachine(  970):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  970):  isHighRSSI       ---> score=65
,E/WifiStateMachine(  970): handleMessage: X
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -57, 3
D/WifiWatchdogStateMachine(  970): RSSI current: 3 new: -57, 3
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1221): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  970):  packet count Tx=261 Rx=370
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  970):  packet count Tx=262 Rx=370
D/WIFI_ICON( 1221): WifiActivity: 2
E/WifiTrafficPoller(  970): notifying of data activity 2
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/Process (  970): killProcessQuiet, pid=6969,
I/ActivityManager(  970): Killing 6969:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 6969
,D/Process (  970): killProcessQuiet, pid=7052,
I/ActivityManager(  970): Killing 7052:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PMS     (  970): Going to sleep due to screen timeout (uid 1000)...,
I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2e01600e
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2e01600e, eanble = 0, strlen(mName) = 91
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@11cf959a
W/SensorService(  970): Listener[1] = com.htc.smartdim.sensor_eye@11d19342
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMN     (  970): goingToSleep
,W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/ActivityManager(  970): Recipient 7052
,I/PMS     (  970): Sleeping (uid 1000)...,
D/XAN-DPS (  970): prepareColorFade 1
,I/Adreno-EGL(  970): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  970): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  970): Build Date: 03/09/15 Mon
I/Adreno-EGL(  970): Local Branch: 
I/Adreno-EGL(  970): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  970): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  970):                  d74aa161a12b9c6fc6332151
W/PMS     (  970): mWirelessDisplayManager is null
W/PMS     (  970): mWirelessDisplayManager is still null
D/PMS     (  970): acquireWL(5e7405): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 970 1000 null
,W/PMN     (  970): goingToSleep done
,W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  970): releaseWL(5e7405): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,E/WifiTrafficPoller(  970):  packet count Tx=262 Rx=370,
E/WifiTrafficPoller(  970): notifying of data activity 0
D/AlarmManager(  970): ACTION_SCREEN_ON
I/AlarmManager(  970): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  970): [AlarmQueuing] done recovering
I/AlarmManager(  970): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  970): [AlarmQueuing] done EPS screen off alarm recovering
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL true Token 24
E/WifiTrafficPoller(  970):  packet count Tx=262 Rx=370,
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL true Token 3
E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
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
,D/WifiDataStallTracker(  970): updateDataStallInfo: mDataStallTxRxSum={txSum=232 rxSum=204} preTxRxSum={txSum=232 rxSum=204}
D/WifiDataStallTracker(  970): updateDataStallInfo: NONE
D/WifiDataStallTracker(  970): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  970): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
,D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/WifiStateMachine(  970): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  970): handleScreenStateChanged Exit: true
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,V/SRS_Proc(  399): ParamSet string: screen_state=on
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
,I/wpa_supplicant( 1330): environment dirty rate=0 [1][0][0]
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  970): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  970): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131127
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131129
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
D/NetworkPolicy(  970): updateScreenOn: false
V/NetworkPolicy(  970): updateIfacesLocked()
E/WifiStateMachine(  970):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
D/WifiController(  970): handleMessage: E msg.what=155650
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/WifiController(  970): handleMessage: X
D/wpa_supplicant( 1330): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1330): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  970): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=48 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  970): handleMessage: X
,D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7517 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
D/WIFI_ICON( 1221): WifiActivity: 0
,D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false),
,I/jxcore-log( 7077): Test app app.js loaded
I/jxcore-log( 7077): 
D/PMS     (  970): acquireWL(16574b81): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1798 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(2f2a426): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1798 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 7517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  970): releaseWL(16574b81): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): 	Bluetooth MAC address: 90:E7:C4:F6:69:77, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7077): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f624d0 added. We now have 1 listener(s)
,D/XAN-DPS (  970): prepareColorFade done
,D/BluetoothAdapter( 7077): 636035381: getState(). Returning 12
,D/XAN-DPS (  970): setBrightness to 0
I/jxcore-log( 7077): BLE advertisement is supported
I/jxcore-log( 7077): 
D/PMS     (  970): releaseWL(2f2a426): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/chromium( 7077): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ContextImpl( 7517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@11cf959a
,W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM32181 Light sensor
,W/SensorService(  970): pid=970, uid=1000
,W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@11cf959a, eanble = 0, strlen(mName) = 67
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@11d19342
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PowerUsageList:PowerUsageHelper( 7517): MY_DEBUG = false
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
,I/DisplayManagerService(  970): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
V/ActivityManager(  970): Display changed displayId=0
D/DotMatrix( 1329): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1329): [EventService] mbHDMIConnect: false, mCoverOn:false
D/AlarmManager(  970): ACTION_SCREEN_OFF
,I/AlarmManager(  970): [AlarmQueuing] screen off now: 
I/AlarmManager(  970): [AlarmQueuing] data connection: true
I/AlarmManager(  970): [AlarmQueuing] wifi connection: true
E/WifiTrafficPoller(  970): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/WifiDataStallTracker(  970): stopDataStallAlarm 
E/WifiDataStallTracker(  970): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  970): handleMessage: E msg.what=131167
E/WifiStateMachine(  970): processMsg: ConnectedState,
E/WifiStateMachine(  970):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
E/WifiStateMachine(  970):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970): processMsg: DefaultState
,V/SRS_Proc(  399): ParamSet string: screen_state=off
E/audio_a2dp_hw(  399): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  970):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  970):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  970): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1330): SET_SCREEN_ON:Off
I/wpa_supplicant( 1330): htc_wext_set_keepalive +
I/wpa_supplicant( 1330): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1330): getPrivFuncNum +	
I/wpa_supplicant( 1330): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1330): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1330): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1330): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  970): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  970): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  970):     Client/Owner: Client
D/WifiDisplayAdapter(  970):     GroupId: 
D/WifiDisplayAdapter(  970):     Passphrase: 
D/WifiDisplayAdapter(  970):     SessionId: 0
D/WifiDisplayAdapter(  970):     IP Address: }
D/SmartSyncUtils( 7517): isEpsOn(), nState = 0
,D/WifiStateMachine(  970): backgroundScan enabled=true startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  970): handleScreenStateChanged Exit: false
E/WifiStateMachine(  970): handleMessage: X
E/WifiStateMachine(  970): handleMessage: E msg.what=131154
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  970): handleMessage: X
D/PMS     (  970): acquireWL(1d8c6403): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7517 1000 null
D/WifiController(  970): handleMessage: E msg.what=155651
D/NetworkPolicy(  970): updateScreenOn: false
D/WifiController(  970): processMsg: DeviceActiveState
V/NetworkPolicy(  970): updateIfacesLocked()
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/NetworkManagementService(  970): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@244d55b2, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  970): pid=1221, uid=10041
W/SensorService(  970): Active sensors: size = 4
W/SensorService(  970): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@244d55b2, eanble = 1, strlen(mName) = 57
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  970): Listener[0] = com.htc.smartdim.sensor_eye@11d19342
W/SensorService(  970): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@244d55b2
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  970): releaseWL(1d8c6403): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
D/DotMatrix( 1329): [EventService] getTotalRam: 1842 Mb
D/SmartDim(  970): Init customizeScreenOffDelayClass error
D/GpsLocationProvider(  970): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/ContactMessageStore( 1569): start background delete task...
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false)
,D/PMS     (  970): acquireWL(3891af80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1798 10024 WorkSource{10024 com.google.android.gms},
D/ContactMessageStore( 1569): size: 0 , 0
D/PMS     (  970): releaseWL(3891af80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1569): Background delete complete
D/PMS     (  970): acquireWL(3680e9b9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1798 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3680e9b9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145),
,D/AutoSetting( 1530): service - mHandler: cancel location update
D/AutoSetting( 1530): service -           changes count: 0
,I/RemoteViews( 1221): apply : com.htc.updater 1 12 1 36,
,W/ContextImpl( 7517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 7517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155
E/WifiStateMachine(  970): processMsg: ConnectedState
,E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1312188093] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState,
E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1312188092] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  970): handleMessage: X
,D/SmartSyncUtils( 7517): isEpsOn(), nState = 0
,D/SmartSyncUtils( 7517): isEpsOn(), nState = 0
,W/ContextImpl( 7517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@11d19342
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  970): disable: get sensor name = Accelerometer Sensor
,I/PowerUsageList:PowerUsageHelper( 7517): PowerProfile::POWER_SCREEN_FULL = 154.8,
,W/SensorService(  970): pid=970, uid=1000
,W/SensorService(  970): Active sensors: size = 3
W/SensorService(  970): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@11d19342, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@244d55b2
,W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  970): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  970): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  970): pid=970, uid=1000
W/SensorService(  970): Active sensors: size = 2
W/SensorService(  970): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  970): hTC Gesture Motion HIDI (handle=0x00000013, connections=1),
W/SensorService(  970): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@11d19342, eanble = 0, strlen(mName) = 36
W/SensorService(  970): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  970): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@244d55b2
,E/ActivityThread(  970): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1825ff53 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1825ff53 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  970): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  970): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  970): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  970): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  970): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  970): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  970): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  970): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  970): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  970): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  970): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  970): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  970): 	,at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  970): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  970): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 5,
I/SensorManager(  970): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@11d19342
,D/PowerUsageList:BatterySipperExt( 7517): gen(), null == sipper.uidObj, userId = 0
,D/SmartSyncUtils( 7517): getMobilePolicyEnabled, result = true
,E/WifiTrafficPoller(  970): ADD_CLIENT: 9
,D/WifiService(  970): New client listening to asynchronous messages
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  970): Setting HAL interactive mode to false
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  970): Setting HAL interactive mode to false done
D/SurfaceControl(  970): Excessive delay in setPowerMode(): 317ms
D/PMS     (  970): Setting HAL auto-suspend mode to true
W/HtcSystemUPManager(  970): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  970): Setting HAL auto-suspend mode done
D/HABCtrl (  970): TPE algorithm. remove timeout.
D/PMS     (  970): OOBE c monitor 11
,D/PMS     (  970): acquireWL(3b2243ac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/InputMethodManagerService(  970): screenObserver, isScreenOn=false
,D/StatusBarManagerService(  970): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/BatteryService(  970): n_update end
I/InputMethodManagerService(  970): Disable input method client, pid=7077
D/PMS     (  970): releaseWL(3b2243ac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo
I/InputMethodManager( 7077): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{253fc52b VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1de53cc9
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
,I/InputManager(  970): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,D/NfcService( 1583): ScreenObserver: OFF
,D/NfcService( 1583): applyRouting - 0
,I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,D/PMS     (  970): acquireWL(213d6875): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1583 1027 null
D/NfcService( 1583): applyRouting -2
D/NfcService( 1583): applyRouting
D/NfcService( 1583): Ignore this applyRouting...
,D/PMS     (  970): releaseWL(213d6875): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/ClockController( 1221): stop clock update:screen off,
,D/PowerUsageList:PowerUsageHelper( 7517): MY_DEBUG = false,
,I/ActivityManager(  970): Killing 7183:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  970): killProcessQuiet, pid=7183
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 7183,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,E/WifiTrafficPoller(  970): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,D/PMS     (  970): releaseWL(db3fcdd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,E/WifiStateMachine(  970): handleMessage: E msg.what=131155,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2559] from screen [on:0 period:-1312185532] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
,E/WifiStateMachine(  970):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1312185529] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
,E/WifiStateMachine(  970): handleMessage: X
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,D/ContactMessageStore( 1569): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1569): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/WifiDataStallTracker(  970): DATA_MONITOR_POLL false Token 5,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/ActivityManager(  970): Killing 5957:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  970): killProcessQuiet, pid=5957
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 5957
,E/WifiStateMachine(  970): handleMessage: E msg.what=131165,
E/WifiStateMachine(  970): processMsg: ConnectedState
E/WifiStateMachine(  970):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: ConnectModeState
E/WifiStateMachine(  970):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: DriverStartedState
,E/WifiStateMachine(  970):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: SupplicantStartedState
E/WifiStateMachine(  970):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): processMsg: DefaultState
E/WifiStateMachine(  970):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  970): handleMessage: X
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  970): acquireWL(1c77500a): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{10024},
V/AlarmManager(  970): sending alarm PendingIntent{2aec507b: PendingIntentRecord{145ee98 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=145022, Int=0
D/PMS     (  970): releaseWL(1c77500a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/AutoSetting( 1530): service - handleMessage() stop self,
,D/AutoSetting( 1530): service - handleMessage() quit looper
,D/AutoSetting( 1530): service - onDestroy() END,
,D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  970): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  970): acquireWL(3b0916f1): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 970 1000 null
,D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  970): [NET] android_getaddrinfofornet-, err=8
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  970): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  970): [NET] android_getaddrinfo_proxy+,
D/libc    (  970): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  970): [NET] android_getaddrinfo_proxy-, success
D/libc    (  970): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  970): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  970): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  970): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  970): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  970):  [handleDownloadXtraData]inject done.
D/PMS     (  970): acquireWL(1c07312d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 970 1000 null
D/GpsLocationProvider(  970): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  970): releaseWL(3b0916f1): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/PMS     (  970): releaseWL(1c07312d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  970): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,E/WifiStateMachine(  970): handleMessage: E msg.what=131326
E/WifiStateMachine(  970): processMsg: ConnectedState,
E/WifiStateMachine(  970):  ConnectedState what:131326 2 0
E/WifiStateMachine(  970): processMsg: L2ConnectedState
E/WifiStateMachine(  970):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  970): handleMessage: X
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  970): acquireWL(15d9d662): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(15d9d662): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): updateBatteryInfo,
D/UsbnetService(  970): BroadcastReceiver::onReceive+,
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  970): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): << updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/TelephonyReceiver( 1569): switchBindHtcMsgCursor: null,
,D/PMS     (  970): acquireWL(1ede53f3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{909c82e: PendingIntentRecord{15bc6fcf android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149846, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{32ff8b0: PendingIntentRecord{152b329 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454681779544, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{3d82f6ae: PendingIntentRecord{10803c4f android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203585, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{d13efdc: PendingIntentRecord{4ba58e5 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=193137, Int=0
D/PMS     (  970): acquireWL(308bcfba): PARTIAL_WAKE_LOCK  *backup* 0x1 970 1000 null
,D/PMS     (  970): acquireWL(28ae4e6b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  970): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  970): Requested init for com.google.android.gms.backup.BackupTransportService but not found,
D/PMS     (  970): releaseWL(308bcfba): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  970): acquireWL(3fde2dc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1ede53f3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  970): releaseWL(28ae4e6b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  970): releaseWL(3fde2dc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(12a89c12): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(12a89c12): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(19441fe3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(104aede0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(1d70675e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(19441fe3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(2aa1080c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(2aa1080c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1963): Vacuum at: now=1454681814007 tag=VacuumService
,I/GoogleURLConnFactory( 1963): Using platform SSLCertificateSocketFactory
,D/PMS     (  970): releaseWL(104aede0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(3c4c4555): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(3c4c4555): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(1e579b6a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(1e579b6a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1963): No account for auth token provided
,D/libc    ( 1963): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1963): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1963): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1963): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1963): [NET] android_getaddrinfo_proxy+
D/libc    ( 1963): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 1963): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1963): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1963): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1963): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1963): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1963): No account for auth token provided,
,W/Uploader( 1963): No account for auth token provided,
,W/Uploader( 1963):  no longer exists, so no auth token.,
,W/Uploader( 1963): No account for auth token provided,
,I/GLSUser ( 1963): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1963): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1963): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1963): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,E/Uploader( 1963): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1963): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1963): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1963): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1963): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1963): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1963): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1963): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1963): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1963): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1963): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1963): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1963): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
E/Uploader( 1963): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1963): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1963): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1963): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1963): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1963): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,W/Uploader( 1963): No account for auth token provided,
,I/GLSUser ( 1963): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1963): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1963): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1963): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1963): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1963): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1963): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1963): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1963): ,	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1963): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235),
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1963): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1963): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,D/PMS     (  970): releaseWL(1d70675e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  970): acquireWL(88f8b72): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(88f8b72): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): acquireWL(2dc74bc3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(2dc74bc3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1530): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@38c0fc92
,D/Process (  970): killProcessQuiet, pid=7211
I/ActivityManager(  970): Killing 7211:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 7211
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  970): acquireWL(12c2dc40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(12c2dc40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  970): acquireWL(35937779): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(35937779): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
,D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/PowerUI ( 1221): closing low battery warning: level=100
I/HtcPowerSaver(  970): << updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1330): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/WifiMonitor(  970): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  970): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  970): acquireWL(1ec6ecbe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{909c82e: PendingIntentRecord{15bc6fcf android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209846, Int=0
,V/AlarmManager(  970): sending alarm PendingIntent{2a197c6c: PendingIntentRecord{184b1235 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454681953015, Int=0
,D/PMS     (  970): releaseWL(1ec6ecbe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  970): acquireWL(18116ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
,D/PMS     (  970): releaseWL(18116ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
,D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652,
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1963): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1963): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1963): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1963): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1963): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1963): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1963): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1963): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1963): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1963): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1963): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 6381): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 6381): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6381): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6381): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6381): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6381): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6381): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1221): reapply : com.google.android.gms 4 40
,W/System  ( 6381): Ignoring header User-Agent because its value was null.,
D/libc    ( 6381): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6381): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6381): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6381): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6381): [NET] android_getaddrinfo_proxy+
D/libc    ( 6381): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6381): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  970): acquireWL(3baad89c): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000}
,V/AlarmManager(  970): sending alarm PendingIntent{34d64b3e: PendingIntentRecord{3a1f1d9f android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=380143, Int=0
D/PMS     (  970): acquireWL(1a65f2a5): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 970 1000 null
D/PMS     (  970): acquireWL(1df4c67a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 970 1000 null
,D/PMS     (  970): releaseWL(3baad89c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
D/PMS     (  970): releaseWL(1a65f2a5): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  970): releaseWL(1df4c67a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  970): acquireWL(120dde2b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(120dde2b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  970): updateBatteryInfo
D/WifiController(  970): handleMessage: E msg.what=155652
,D/PMS     (  970): runPSCheck
D/WifiController(  970): processMsg: DeviceActiveState
D/HtcPowerSaver(  970): Checking...
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  970): processMsg: StaEnabledState
,D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  970): acquireWL(29dae288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(29dae288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo,
D/UsbnetService(  970): BroadcastReceiver::onReceive+,
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
,D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1569): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1569): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1569): sku_id=118
D/ContactMessageStore( 1569): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1569): start background delete task...
,D/ContactMessageStore( 1569): size: 0 , 0
,D/ContactMessageStore( 1569): Background delete complete
,D/PMS     (  970): acquireWL(681421): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(681421): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  970): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(14f8d046): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(14f8d046): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  970): acquireWL(198a3207): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(198a3207): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
,D/UsbnetService(  970): BroadcastReceiver::onReceive+,
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/NotificationService(  970): plugged=true pluggin=true
,D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  970): Checking...
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(337f9f34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(337f9f34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HtcPowerSaver(  970): updateBatteryInfo,
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  970): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(2610d15d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{909c82e: PendingIntentRecord{15bc6fcf android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=389846, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{1fe1aad2: PendingIntentRecord{58de7a3 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=943266, Int=0
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/bt-btm  ( 3330): Received oneshot timer event complete
,I/bt-btm  ( 3330): btm_ble_timeout
I/bt-btm  ( 3330): btm_gen_resolvable_private_addr
D/PMS     (  970): releaseWL(2610d15d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1002}
,D/PMS     (  970): acquireWL(25117aa0): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3330 1002 null
,D/bt-btm  ( 3330): btm_ble_rand_enc_complete
I/bt-btm  ( 3330): btm_gen_resolve_paddr_low
D/bt-smp  ( 3330): smp_encrypt_data
W/bt-smp  ( 3330): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 3330): Plain text(LSB ~ MSB) = 80 ee 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3330): Encrypted text(LSB ~ MSB) = d6 86 28 21 e5 d7 03 22 34 d2 ff 58 a2 9c 7e 69 
I/bt-btm  ( 3330): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3330): Stopping oneshot timer
D/bt-btm  ( 3330): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  970): releaseWL(25117aa0): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  970): acquireWL(138e2659): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
,I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(138e2659): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
,D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(250ba21e): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
V/AlarmManager(  970): sending alarm PendingIntent{194cc27d: PendingIntentRecord{129f1572 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805564, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{909c82e: PendingIntentRecord{15bc6fcf android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=989846, Int=0
V/AlarmManager(  970): sending alarm PendingIntent{128d5aff: PendingIntentRecord{1823a0cc com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010624, Int=0
,I/ActivityManager(  970): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7578 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  970): sending alarm PendingIntent{bf1cf15: PendingIntentRecord{24bc22a com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454682276522, Int=0
,D/PMS     (  970): acquireWL(25e6a81b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(25e6a81b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  970): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=7595 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  970): sending alarm PendingIntent{a4ffdb8: PendingIntentRecord{37ad4791 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  970): sending alarm PendingIntent{2bbbd6f6: PendingIntentRecord{3f360157 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454682578766, Int=0,
,W/ContextImpl( 7517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  970): acquireWL(36e33d64): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1963): Message class com.google.f.a.a.i
D/PMS     (  970): releaseWL(250ba21e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  970): releaseWL(36e33d64): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PowerUsageList:PowerUsageHelper( 7517): MY_DEBUG = false
,D/PowerUsageService( 7517): repeat time = 1454683520900
,I/art     (  970): Explicit concurrent mark sweep GC freed 48155(2MB) AllocSpace objects, 10(1716KB) LOS objects, 33% free, 19MB/28MB, paused 1.787ms total 154.667ms
,I/PowerUsageList:PowerUsageHelper( 7517): PowerProfile::POWER_SCREEN_FULL = 154.8,
,I/ImageRamCache( 7595): create image Cache, size: 31457280.
I/ImageRamCache( 7595): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 7595): create image Cache, size: 31457280.
,I/FeedSettings( 7595): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
I/FeedSettings( 7595): GroupBudget 0.500000 0.380000
I/FeedSettings( 7595): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 7595): changeLocale(): en_GB
D/PowerUsageList:BatterySipperExt( 7517): gen(), null == sipper.uidObj, userId = 0
,I/Prism.AllAppsOptionsMa_( 7595): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 7595): loadGridSize() with Alternative
,E/cutils-trace( 7627): Error opening trace file: Permission denied (13)
I/dex2oat ( 7627): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7627): dex2oat: override thread count:4,
,D/libc    ( 7595): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4,
D/libc    ( 7595): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 7595): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    ( 7595): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 7595): [NET] android_getaddrinfo_proxy+
,D/libc    ( 7595): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  393): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  393): [NET] android_getaddrinfofornet-, SUCCESS,
,D/libc    ( 7595): [NET] android_getaddrinfo_proxy-, success
,I/dex2oat ( 7627): dex2oat took 706.188ms (threads: 4),
,D/Process (  970): killProcessQuiet, pid=7152,
I/ActivityManager(  970): Killing 7152:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/ActivityManager(  970): Recipient 7152
,I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 7578): ApplicationMonitor {bfe973b}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 7578): PnsModel {105f79ca}: update(): Update registration caused by: alarm,
,I/PushClient( 7578): PnsConfigModel {27150fe9}: <init>(): Use dm-client for provisioning.,
,W/System.err( 7578): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 7578): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 7578): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 7578): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  970): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7638 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 7638): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7638 dbg=false s=true,
,I/DeviceManagement( 7638): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 7638): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 7638): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 7638): WorkflowService: Starting workflow service
,I/DeviceManagement( 7638): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@383a676c] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 7638): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 7638): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 7638): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 7638): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7638): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 7638): SessionStateController: Checking invariants...,
,I/DeviceManagement( 7638): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 7638): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@383a676c]
,I/DeviceManagement( 7638): WorkflowService: Stopping workflow service,
,D/Process (  970): killProcessQuiet, pid=7320
I/ActivityManager(  970): Killing 7320:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
,D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 7578): PnsModel {105f79ca}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  970): Recipient 7320,
,D/Process (  970): killProcessQuiet, pid=7380,
I/ActivityManager(  970): Killing 7380:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  970): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  970): Recipient 7380
,D/PMS     (  970): acquireWL(175444df): PARTIAL_WAKE_LOCK  *alarm* 0x1 970 1000 WorkSource{1000},
D/SmartSyncUtils( 7517): isEpsOn(), nState = 0
V/AlarmManager(  970): sending alarm PendingIntent{3f57752c: PendingIntentRecord{29f87bf5 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454682625254, Int=0
,D/PMS     (  970): releaseWL(175444df): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PMS     (  970): acquireWL(290f9d8a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7517 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 7517): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 7517): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 7517): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 7517): SettingOnTime = 1454738400000, randomSettingOnTime = 1454736169000
D/SmartSyncScreenOnOffTimeReceiver( 7517): SettingOffTime = 1454716800000, randomSettingOffTime = 1454722942000
,D/SmartSyncScreenOnOffTimeReceiver( 7517): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 7517): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 7517): bNightModeTurnOffOnce = false
,D/PMS     (  970): releaseWL(290f9d8a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,W/SQLiteConnectionPool( 7595): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/PMS     (  970): acquireWL(20624ffb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  970): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): releaseWL(20624ffb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/PMS     (  970): runPSCheck
D/WifiController(  970): handleMessage: E msg.what=155652
D/HtcPowerSaver(  970): Checking...
D/WifiController(  970): processMsg: DeviceActiveState
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
D/WifiController(  970): handleMessage: X
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(155cb818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null,
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(155cb818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  970): runPSCheck
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  970): Checking...
I/HtcPowerSaver(  970): >> updateStatus
D/PowerUI ( 1221): closing low battery warning: level=100
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(1321e271): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(1321e271): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  970): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  970): plugged=true pluggin=true
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
D/PMS     (  970): runPSCheck
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  970): >> updateStatus
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  970): battery changed pluggedType: 2
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  970): acquireWL(cd20856): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
D/UsbnetService(  970): BroadcastReceiver::onReceive+
I/BatteryService(  970): n_update end
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): releaseWL(cd20856): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive-
D/NotificationService(  970): plugged=true pluggin=true
D/WifiController(  970): handleMessage: E msg.what=155652
D/PMS     (  970): runPSCheck
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  970): Checking...
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  970): >> updateStatus
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): battery changed pluggedType: 2
,D/WifiController(  970): processMsg: StaEnabledState
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  970): processMsg: DefaultState
I/HtcPowerSaver(  970): << updateStatus
D/WifiController(  970): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  970): User[0] Flushing usage stats to disk
,D/PMS     (  970): acquireWL(3c7bf0d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 970 1000 null
I/BatteryService(  970): n_update end
D/PMS     (  970): releaseWL(3c7bf0d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  970): updateBatteryInfo
D/UsbnetService(  970): BroadcastReceiver::onReceive+
D/NotificationService(  970): plugged=true pluggin=true
D/UsbnetService(  970): onReceive BATTERY_CHANGED
D/PMS     (  970): runPSCheck
D/UsbnetService(  970):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  970): Checking...
D/UsbnetService(  970): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  970): >> updateStatus
D/WifiController(  970): handleMessage: E msg.what=155652
D/WifiController(  970): battery changed pluggedType: 2
D/WifiController(  970): processMsg: DeviceActiveState
D/WifiController(  970): processMsg: StaEnabledState
D/WifiController(  970): processMsg: DefaultState
D/WifiController(  970): handleMessage: X
D/HeadsetStateMachine( 3330): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1221): closing low battery warning: level=100
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  970): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  970): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  970): acquireWL(21713dc4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 970 1000 WorkSource{1000}
V/AlarmManager(  970): sending alarm PendingIntent{909c82e: PendingIntentRecord{15bc6fcf android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1049846, Int=0,
V/AlarmManager(  970): sending alarm PendingIntent{7a134ad: PendingIntentRecord{4ba58e5 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=1307704, Int=0
,D/PMS     (  970): acquireWL(87e53e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(21713dc4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  970): acquireWL(1e24c373): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(87e53e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1963): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement,
I/GLSUser ( 1963): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1963): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1963): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1963): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 4675): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication,
,D/PMS     (  970): releaseWL(1e24c373): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): acquireWL(14277992): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  970): releaseWL(14277992): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  970): acquireWL(34c56f63): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1963 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  970): releaseWL(34c56f63): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,TIME-OUT KILL (timeout was 1200000ms)
```
