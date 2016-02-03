#### Test 58135655c662d33_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1481): handler message = 4011
E/HtcModeClient( 1481): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 1481): Don't start project servcice
D/HtcModeClient( 1481): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1481): connectState: CONNECTION_READY = false
D/SilentMusic( 1481): call stop
D/HtcModeClient( 1481): close connection
W/HtcModeClient( 1481): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 1481): read the terminate packet, so break
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 52
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 52
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,E/cutils-trace( 4535): Error opening trace file: No such file or directory (2)
--------- beginning of /dev/log/system
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/CustomizationManager( 4535): ====startRecUseTime====
D/htc.customization.log.level( 4535):  is 
W/CustomizationLogLevel( 4535): Level value is invalid, use default level 2
D/CustomizationManager( 4535):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4535): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4535): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4535): Parsing tag category name = system
I/CustomizationCIDLoader( 4535): Parsing tag category name = application
I/CustomizationCIDLoader( 4535): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4535): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4535): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4535): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4535): Parsing tag category name = Settings
D/CustomizationManager( 4535):  Read CID file spent 0.112 (s)
D/CustomizationManager( 4535):  All configurations done spent 0.112 (s)
W/HtcNativeFlag( 4535): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4535): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4535): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4535): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4535
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 52
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 104
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{426961f8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 52
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 156
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): acquireWL(4235ec98): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  906): releaseWL(4235ec98): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4267fb68): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  906): releaseWL(4267fb68): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42666bf0): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  906): releaseWL(42666bf0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42612bf0): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  906): releaseWL(42612bf0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 52
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 208
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(4269b200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42561a60: PendingIntentRecord{423a66f0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104524, Int=0
,D/PMS     (  906): releaseWL(4269b200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=174 rxSum=159} preTxRxSum={txSum=173 rxSum=158}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20353 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20354 delay=15s
,D/PMS     (  906): acquireWL(4235e1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{4266b058: PendingIntentRecord{420512e0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454523147167, Int=563223000
,D/PMS     (  906): acquireWL(425eb280): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2250 10028 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4551 uid=10077 gids={50077}
,V/AlarmManager(  906): sending alarm PendingIntent{424e0158: PendingIntentRecord{42518d58 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454523163307, Int=60000
,D/PMS     (  906): releaseWL(4235e1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(425fedc0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2250 10028 null
,D/PMS     (  906): releaseWL(425eb280): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,I/CheckinService( 2250): Preparing to send checkin request
,I/EventLogService( 2250): Accumulating logs since 1454523113307
,W/EventLogAggregator( 2250): Unknown tag: install_package_attempt
,W/EventLogAggregator( 2250): Unknown tag: snet
,W/EventLogAggregator( 2250): Unknown tag: snet_gcore
,D/SMSBackup( 4551): SMSBackupAgentService started
,D/SMSBackup( 4551): Checking restore status
,D/SMSBackup( 4551): Restore complete
,D/SMSBackup( 4551): cancelCheckAlarm
,D/SMSBackup( 4551): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3818
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3818:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3818
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GoogleHttpClient( 2250): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2250): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2250/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2250/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1358): GoogleAccountDataService.getToken()
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1358): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2250): awaiting user notification for token
D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b2bd10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 7 3 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4565 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4565): install
,I/MultiDex( 4565): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4565): loading existing secondary dex files
,I/MultiDex( 4565): load found 1 secondary dex files
,I/MultiDex( 4565): install done
,I/ProviderInstaller( 4565): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/Settings( 4565): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4565/10028)
,I/CheckinTask( 2250): Sending checkin request (8879 bytes)
,D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-,err=8
D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2250): [NET] getaddrinfo-, 1
,D/libc    ( 2250): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =5e3e +++++
,D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2250): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): acquireWL(426bb940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
,D/PMS     (  906): releaseWL(426bb940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2250/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2250/10028)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=10 [20][2][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 58
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 266
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:237, mTXpacketCount:212, avgLinkspeed:53,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,W/GLSUser ( 1358): GoogleAccountDataService.getToken()
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1358): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1358): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2250): awaiting user notification for token
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b2c3a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 7 2 12
,I/CheckinTask( 2250): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2250): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(425fedc0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2250): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c37d80 that was originally bound here
E/ActivityThread( 2250): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c37d80 that was originally bound here
E/ActivityThread( 2250): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2250): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2250): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2250): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2250): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2250): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2250): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2250): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2250): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2250): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2250): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2250): 	at bks.a(SourceFile:298)
E/ActivityThread( 2250): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2250): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2250): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1358): GCM config loaded
,I/SensorManager(  906): mEventCount = 1200
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 58
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 58
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420aa8c8
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420aa8c8, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e97560
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4260b7f8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/Process (  906): killProcessQuiet, pid=4212
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4212:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4212
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 370ms
,W/PnPMgr  (  354): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=1266
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@427d8118)
,D/NfcService( 1254): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMS     (  906): acquireWL(427d7900): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMN     (  906): wakingUp
D/PMS     (  906): releaseWL(427d7900): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
,D/PMS     (  906): acquireWL(427d9588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMN     (  906): onScreenOn
,D/PMS     (  906): releaseWL(427d9588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 1991): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1991): [MTP][onReceive]-
D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/AutoSetting( 1397): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
D/HtcPowerSaver(  906): updateBatteryInfo
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): acquireWL(427e0708): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,D/PMS     (  906): releaseWL(427e0708): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1397): service - onCreate()
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
I/ClockThread( 1115): stop update clock
D/AutoSetting( 1397): service - AddressCache: using context: com.htc.Weather
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20355 delay=15s
D/TetherSettings( 4316): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4316): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4316): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4316): Cust_ConnectToPC   : spcsc>false
D/        ( 4316): Cust_ConnectToPC   : IPT>true
,D/        ( 4316): Cust_ConnectToPC   : Singel_USB>false
,D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
I/wpa_supplicant( 1166): SET_SCREEN_ON:On
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): BG scan when screen On
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): Match BG scan, scan!
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
W/Settings( 4316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/SmartNS_Utility( 4316): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4316): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4316): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/LocationManagerService(  906): request 42022cc8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
,I/PSReceiver( 4316): onReceive:android.intent.action.USER_PRESENT
,D/WIFI_ICON( 1115): WifiActivity: 1
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
,D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  373): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/SmartNS_PSService( 4316): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4316):  defaultType:0
W/ContextImpl( 4316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  906): updateScreenOn: false
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4595 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(427f58c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
,D/PMS     (  906): releaseWL(427f58c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1818): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1818): onScreenOn: 1454523170510
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1818): onScreenOn: 1454523170510
W/ContextImpl( 4595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e97560
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41e97560, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4260b7f8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(427f8520): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/FeedHostManager( 1266): [onPause]
I/FeedProviderManager( 1266): onPause
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20355 mDataStallAlarmIntent=PendingIntent{41f74838: PendingIntentRecord{423a66f0 android broadcastIntent}}
,I/FeedHostManager( 1266): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b5d410
I/SocialFeedProvider( 1266): +onPause
,I/SocialFeedProvider( 1266): -onPause
,D/SmartSyncUtils( 4595): isEpsOn(), nState = 0
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): acquireWL(427fc5d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4595 1000 null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/PMS     (  906): acquireWL(427fefb8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(427f8520): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  906): releaseWL(427fc5d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4595): getMobilePolicyEnabled, result = true
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:Off
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1166): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 58
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 116
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
W/ContextImpl( 4595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4595): isEpsOn(), nState = 0
D/SmartSyncUtils( 4595): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4595): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4260b7f8
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4260b7f8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4260b7f8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4260b7f8
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4261e388 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4261e388 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1818): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1818): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1818): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1818): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1818): onScreenOff
D/PMS     (  906): acquireWL(4281ea28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
,D/PMS     (  906): releaseWL(4281ea28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1397): service - mHandler: cancel location update
D/AutoSetting( 1397): service -           changes count: 0
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(427fefb8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-81
D/wpa_supplicant( 1166): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1166): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1166): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1166): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1166): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplican,t( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-81
D/wpa_supplicant( 1166): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1166): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1166): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1166): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1166): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: DISCONNECTED -> INACTIVE
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428224f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@428224f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@428224f0 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1166): reply (631) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000022230933
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000114295289
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-81
I/wpa_supplicant( 1166): tsf=0000000114295311
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-57
I/wpa_supplicant( 1166): tsf=0000000114295277
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-77
I/wpa_supplicant( 1166): tsf=0000000114295301
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 22230933, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 114295289, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -81, frequency: 2437, timestamp: 114295311, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 114295277, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 114295301, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 5 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  78, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-81], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/AutoSetting( 1481): service - handleMessage() stop self
,D/AutoSetting( 1481): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4384
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1481): service - handleMessage() quit looper
I/ActivityManager(  906): Killing 4384:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4384
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3997
I/ActivityManager(  906): Killing 3997:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3997
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4282e9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dbe88: PendingIntentRecord{42284de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=121691, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4282e9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{427e19d0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-85
D/wpa_supplicant( 1166): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1166): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1166): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1166): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1166): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1166): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
,I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-85
D/wpa_supplicant( 1166): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1166): Add randomness: count=22 entropy=16
,D/wpa_supplicant( 1166): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1166): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1166): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1166): reply (631) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000131765203
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000131765240
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-85
I/wpa_supplicant( 1166): tsf=0000000131765260
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS],
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
,I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-57
I/wpa_supplicant( 1166): tsf=0000000131765230
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
,I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-77
I/wpa_supplicant( 1166): tsf=0000000131765250
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 131765203, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 131765240, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -85, frequency: 2437, timestamp: 131765260, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 131765230, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 131765250, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  76, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-85], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426558c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+,
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  906): updateBatteryInfo,
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PMS     (  906): releaseWL(426558c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425eea88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42498ec8: PendingIntentRecord{41bd7318 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141811, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41ed4ef8: PendingIntentRecord{425c1f20 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142978, Int=0
,D/AutoSetting( 1397): service - handleMessage() stop self
,D/AutoSetting( 1397): service - handleMessage() quit looper
,D/AutoSetting( 1397): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4414
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4414:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4414
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(425b3170): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10028)
D/PMS     (  906): releaseWL(425eea88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(41aad0b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10028 null
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =5244 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/PMS     (  906): releaseWL(41aad0b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  366): [NET]res_nsend:resplen=238
D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): releaseWL(425b3170): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-80
D/wpa_supplicant( 1166): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1166): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1166): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1166): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1166): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (5 BSSes)
D/wpa_supp,licant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-80
D/wpa_supplicant( 1166): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=31 entropy=25
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1166): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1166): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1166): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1166): Add randomness: count=35 entropy=29
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1166): reply (631) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000149225333
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166,): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000149225369
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-80
I/wpa_supplicant( 1166): tsf=0000000149225389
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-57
I/wpa_supplicant( 1166): tsf=0000000149225359
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-77
I/wpa_supplicant( 1166): tsf=0000000149225379
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ####
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 149225333, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 149225369, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -80, frequency: 2437, timestamp: 149225389, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 149225359, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 149225379, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  78, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-80], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1166): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1166): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1166): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1166): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1166): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1166): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wl,an0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1166): BSS: last_scan_res_used=6/32 last_scan_full=0
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1166): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1166): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1166): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1166): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1166): Add randomness: count=46 entropy=40
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1166): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1166): reply (773) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000166721244
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id,=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000166721280
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-79
I/wpa_supplicant( 1166): tsf=0000000166721299
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000166721269
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-78
I/wpa_supplicant( 1166): tsf=0000000166721290
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-90
I/wpa_supplicant( 1166): tsf=0000000166721309
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 166721244, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 166721280, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 166721299, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 166721269, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 166721290, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 166721309, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-79], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/PMS     (  906): acquireWL(42664cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42664cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426bb140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{425bfb48: PendingIntentRecord{4250f7e8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175262, Int=0
,D/PMS     (  906): releaseWL(426bb140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(425678e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dbe88: PendingIntentRecord{42284de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=181692, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425678e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1166): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1166): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1166): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1166): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1166): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1166): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wl,an0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1166): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1166): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1166): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1166): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1166): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1166): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0,
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6,
I/wpa_supplicant( 1166): reply (773) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000184144850
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000184144887
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-79
I/wpa_supplicant( 1166): tsf=0000000184144907
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
,I/wpa_supplicant( 1166): tsf=0000000184144876
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-78
I/wpa_supplicant( 1166): tsf=0000000184144897
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
,I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-90
I/wpa_supplicant( 1166): tsf=0000000184144917
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 184144850, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 184144887, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 184144907, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 184144876, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 184144897, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 184144917, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-79], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426837c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426837c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-80
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-88
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1166): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1166): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1166): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1166): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1166): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1166): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1166): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1166): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=,0 caps=0x411
D/wpa_supplicant( 1166): 5: 8c:04:ff:b9:af:25 ssid='SALVADOR' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1166): 6: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 7: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (8 BSSes)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1166): nl80211: Survey data missing
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-80
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-88
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1166): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1166): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1166): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1166): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1166): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1166): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1166): Add randomness: count=75 entropy=69
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1166): reply (1037) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000201685498
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000201685536
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-80
I/wpa_supplicant( 1166): tsf=0000000201685545
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000201685525
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-82
I/wpa_supplicant( 1166): tsf=0000000201685555
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-90,
I/wpa_supplicant( 1166): tsf=0000000201685565
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=6
I/wpa_supplicant( 1166): bssid=8c:04:ff:b9:af:25
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-88
I/wpa_supplicant( 1166): tsf=0000000201685574
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=SALVADOR
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=7
I/wpa_supplicant( 1166): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000201685585
I/wpa_supplicant( 1166): flags=[WPA2-EA
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 201685498, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 201685536, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -80, frequency: 2437, timestamp: 201685545, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 201685525, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 201685555, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 201685565, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: SALVADOR, BSSID: 8c:04:ff:b9:af:25, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 201685574, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 201685585, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  78, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-80], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                         SALVADOR [8c:04:ff:b9:af:25], Rssi:  4 [-88], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-88
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1166): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1166): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1166): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1166): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1166): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1166): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 8c:04:ff:b9:af:25 ssid='SALVADOR' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1166): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x5,11
D/wpa_supplicant( 1166): 6: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-88
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1166): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1166): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1166): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1166): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1166): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1166): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1166): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/Wi,fiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1166): reply (1037) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000218862661
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000218862688
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-79
I/wpa_supplicant( 1166): tsf=0000000201685545
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000201685525
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-82
I/wpa_supplicant( 1166): tsf=0000000218862710
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-90
I/wpa_supplicant( 1166): tsf=0000000218862721
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=6
I/wpa_supplicant( 1166): bssid=8c:04:ff:b9:af:25
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-88
I/wpa_supplicant( 1166): tsf=0000000218862732
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=SALVADOR
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=7
I/wpa_supplicant( 1166): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000218862742
I/wpa_supplicant( 1166): flags=[WPA2-EA
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 218862661, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 218862688, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 201685545, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 201685525, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 218862710, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 218862721, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  906): 6: scan result = SSID: SALVADOR, BSSID: 8c:04:ff:b9:af:25, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 218862732, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 218862742, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 8 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-79], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                         SALVADOR [8c:04:ff:b9:af:25], Rssi:  4 [-88], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (8) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(427f8718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427f8718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-80
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-88
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1166): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1166): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1166): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1166): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1166): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1166): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 8c:04:ff:b9:af:25 ssid='SALVADOR' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1166): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x5,11
D/wpa_supplicant( 1166): 6: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-80
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-88
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1166): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1166): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1166): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1166): Add randomness: count=101 entropy=95
D/wpa_supplicant( 1166): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1166): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1166): reply (924) for get BSS: id=0,
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000218862661
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000236032909
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-80
I/wpa_supplicant( 1166): tsf=0000000236032921
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS],
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-82
I/wpa_supplicant( 1166): tsf=0000000218862710
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-90
I/wpa_supplicant( 1166): tsf=0000000236032942
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=6
I/wpa_supplicant( 1166): bssid=8c:04:ff:b9:af:25
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-88
I/wpa_supplicant( 1166): tsf=0000000236032952
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=SALVADOR
I/wpa_supplicant( 1166): ====
,I/wpa_supplicant( 1166): id=7
I/wpa_supplicant( 1166): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000236032961
I/wpa_supplicant( 1166): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC Wi-Free
I/wpa_supplicant( 1166): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 218862661, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 236032909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -80, frequency: 2437, timestamp: 236032921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 218862710, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 236032942, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: SALVADOR, BSSID: 8c:04:ff:b9:af:25, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 236032952, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 236032961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  78, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  6 [-80], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                         SALVADOR [8c:04:ff:b9:af:25], Rssi:  4 [-88], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  69, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426d0b98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dbe88: PendingIntentRecord{42284de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=241692, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426d0b98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(4281e448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4281e448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1166): Add randomness: count=105 entropy=99
D/wpa_supplicant( 1166): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1166): Add randomness: count=107 entropy=101
D/wpa_supplicant( 1166): Add randomness: count=108 entropy=102
D/wpa_supplicant( 1166): Add randomness: count=109 entropy=103
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_suppl,icant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1166): Add randomness: count=111 entropy=105
D/wpa_supplicant( 1166): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1166): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1166): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1166): Add randomness: count=115 entropy=109
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1166): reply (924) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000253545607
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000253545633
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-79
I/wpa_supplicant( 1166): tsf=0000000236032921
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-82
I/wpa_supplicant( 1166): tsf=0000000253545654
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000253545676
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=6
I/wpa_supplicant( 1166): bssid=8c:04:ff:b9:af:25
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-88
I/wpa_supplicant( 1166): tsf=0000000236032952
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=SALVADOR
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=7
I/wpa_supplicant( 1166): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000253545664
I/wpa_supplicant( 1166): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC Wi-Free
I/wpa_supplicant( 1166): ####
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 253545607, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 253545633, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 236032921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 253545654, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 253545676, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: SALVADOR, BSSID: 8c:04:ff:b9:af:25, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 236032952, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  906): 6: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 253545664, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  80, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-79], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                         SALVADOR [8c:04:ff:b9:af:25], Rssi:  4 [-88], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  69, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  69, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1166): Add randomness: count=117 entropy=111
D/wpa_supplicant( 1166): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1166): Add randomness: count=119 entropy=113
D/wpa_supplicant( 1166): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1166): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_sup,plicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1166): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1166): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1166): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1166): Add randomness: count=125 entropy=119
D/wpa_supplicant( 1166): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1166): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelemen,t id=1 len=6
I/wpa_supplicant( 1166): reply (784) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000271025492
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000271025519
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-79
I/wpa_supplicant( 1166): tsf=0000000271025529
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-82
I/wpa_supplicant( 1166): tsf=0000000271025539
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000271025561
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=7
I/wpa_supplicant( 1166): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000271025549
I/wpa_supplicant( 1166): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC Wi-Free
I/wpa_supplicant( 1166): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 271025492, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 271025519, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 271025529, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 271025539, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 271025561, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 271025549, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-79], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=128 entropy=122
D/wpa_supplicant( 1166): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1166): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1166): Add randomness: count=131 entropy=125
D/wpa_supplicant( 1166): Add randomness: count=132 entropy=126
D/wpa_supplicant( 1166): Add randomness: count=133 entropy=127
D/wpa_supplicant( 1166): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1166): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0, caps=0x511
D/wpa_supplicant( 1166): 6: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1166): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1166): Add randomness: count=137 entropy=131
D/wpa_supplicant( 1166): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1166): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1166): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1166): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1166): reply (897) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220,
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000288465359
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000288465398
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-79
I/wpa_supplicant( 1166): tsf=0000000288465408
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-82
I/wpa_supplicant( 1166): tsf=0000000288465418
,I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000288465437
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=7
I/wpa_supplicant( 1166): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-89
I/wpa_supplicant( 1166): tsf=0000000288465428
I/wpa_supplicant( 1166): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC Wi-Free
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=8
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-57
I/wpa_supplicant( 1166): tsf=0000000288465386
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 288465359, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 288465398, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 288465408, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 288465418, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 288465437, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 288465428, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 288465386, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-79], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42762d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42762d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4276a140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422dbe88: PendingIntentRecord{42284de0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=301692, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4276a140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
,D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1166): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1166): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1166): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1166): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1166): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1166): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 9
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 0
,I/wpa_supplicant( 1166): wpa_s->is_screen_on 0
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1166): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1166): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1166): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 6: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1166): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1166): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1166): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1166): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1166): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1166): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1166): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1166): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1166): Add randomness: count=153 entropy=147
D/wpa_supplicant( 1166): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1166): Add randomness: count=155 entropy=149
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): clear disabled list - type=1
I/wpa_supplicant( 1166): No suitable network found
W/wpa_supplicant( 1166): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1166): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.andr,oid.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  906): getDiscoveryDongleList
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1166): reply (897) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-45
I/wpa_supplicant( 1166): tsf=0000000305935346
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-56
I/wpa_supplicant( 1166): tsf=0000000305935382
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-79
I/wpa_supplicant( 1166): tsf=0000000305935391
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1166): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1166): ====
,I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2427
I/wpa_supplicant( 1166): level=-82
I/wpa_supplicant( 1166): tsf=0000000305935401
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=5
I/wpa_supplicant( 1166): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-91
I/wpa_supplicant( 1166): tsf=0000000305935421
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC0039325
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=7
I/wpa_supplicant( 1166): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1166): freq=2462
I/wpa_supplicant( 1166): level=-89
I/wpa_supplicant( 1166): tsf=0000000305935411
I/wpa_supplicant( 1166): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=UPC Wi-Free
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=8
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-57
I/wpa_supplicant( 1166): tsf=0000000305935372
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 305935346, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 305935382, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 305935391, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 305935401, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 305935421, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 305935411, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 305935372, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 7 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  80, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-79], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426ebde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(426ebde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-,
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus

```
