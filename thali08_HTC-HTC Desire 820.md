#### Test 58497659c9ea290_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main,
I/HtcModeClient( 1505): handler message = 4011
E/HtcModeClient( 1505): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 1505): Don't start project servcice
D/HtcModeClient( 1505): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1505): connectState: CONNECTION_READY = false
D/SilentMusic( 1505): call stop
D/HtcModeClient( 1505): close connection
W/HtcModeClient( 1505): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 1505): read the terminate packet, so break
E/cutils-trace( 4462): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4462): ====startRecUseTime====
D/htc.customization.log.level( 4462):  is 
W/CustomizationLogLevel( 4462): Level value is invalid, use default level 2
D/CustomizationManager( 4462):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4462): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4462): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4462): Parsing tag category name = system
I/CustomizationCIDLoader( 4462): Parsing tag category name = application
I/CustomizationCIDLoader( 4462): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4462): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4462): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4462): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4462): Parsing tag category name = Settings
D/CustomizationManager( 4462):  Read CID file spent 0.102 (s)
D/CustomizationManager( 4462):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 4462): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4462): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4462): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4462): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4462
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  906): mEventCount = 750
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42bbb768 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): acquireWL(42c46480): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(42c46480): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42c24740): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(42c24740): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42cef860): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(42cef860): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42bef070): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(42bef070): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=121 rxSum=103} preTxRxSum={txSum=121 rxSum=103}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20362 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20363 delay=15s
D/PMS     (  906): acquireWL(42cc3588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42bfc6a0: PendingIntentRecord{4291b578 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104552, Int=0
D/PMS     (  906): releaseWL(42cc3588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c4c5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{4298b468: PendingIntentRecord{42c49940 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454714852015, Int=563223000
,D/PMS     (  906): acquireWL(42c3cdd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2226 10028 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4478 uid=10077 gids={50077}
,V/AlarmManager(  906): sending alarm PendingIntent{42b58ce8: PendingIntentRecord{42bd9fd8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454714868035, Int=60000
,D/PMS     (  906): releaseWL(42c4c5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(42bf5238): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(42c3cdd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
I/CheckinService( 2226): Preparing to send checkin request
I/EventLogService( 2226): Accumulating logs since 1454714817774
,W/EventLogAggregator( 2226): Unknown tag: install_package_attempt
,W/EventLogAggregator( 2226): Unknown tag: snet
,W/EventLogAggregator( 2226): Unknown tag: snet_gcore
,D/SMSBackup( 4478): SMSBackupAgentService started
,D/SMSBackup( 4478): Checking restore status
,D/SMSBackup( 4478): Restore complete
,D/SMSBackup( 4478): cancelCheckAlarm
,D/SMSBackup( 4478): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3650
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3650:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,I/GoogleHttpClient( 2226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2226): Using GMS GoogleHttpClient
I/ActivityManager(  906): Recipient 3650
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2226/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2226/10028)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2226): awaiting user notification for token
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{4228c358 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 3 13 2 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4492 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4492): install
,I/MultiDex( 4492): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4492): loading existing secondary dex files
,I/MultiDex( 4492): load found 1 secondary dex files
,I/MultiDex( 4492): install done
,I/ProviderInstaller( 4492): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/Settings( 4492): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4492): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4492): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4492): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4492): Local Branch: 
I/Adreno-EGL( 4492): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4492): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4492):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4492): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4492): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4492): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4492): Local Branch: 
I/Adreno-EGL( 4492): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4492): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4492):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4492/10028)
,I/Adreno-EGL( 4492): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4492): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4492): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4492): Local Branch: 
I/Adreno-EGL( 4492): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4492): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4492):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2226): Sending checkin request (9017 bytes)
D/libc    ( 2226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2226): [NET] getaddrinfo-,err=8
D/libc    ( 2226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2226): [NET] getaddrinfo-, 1
,D/libc    ( 2226): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =89f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2226): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): acquireWL(42cf3fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
,D/PMS     (  906): releaseWL(42cf3fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2226/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [13][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2226/10028)
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2226): awaiting user notification for token
D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{423df698 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 7 2 12
,I/CheckinTask( 2226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2226): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(42bf5238): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@423758e8 that was originally bound here
E/ActivityThread( 2226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@423758e8 that was originally bound here
E/ActivityThread( 2226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2226): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2226): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2226): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2226): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2226): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2226): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2226): 	at bks.a(SourceFile:298)
E/ActivityThread( 2226): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2226): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2226): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2226): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1359): GCM config loaded
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:172, mTXpacketCount:159, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Process (  906): killProcessQuiet, pid=3786
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3786:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3786
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PMS     (  906): Going to sleep due to screen timeout...
,W/PMS     (  906): mWirelessDisplayManager is null
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42742128
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42742128, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426c3eb0
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42bbd5e8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 371ms
,W/PnPMgr  (  352): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
,D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): OOBE c monitor 11
V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42e33820)
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
D/PMN     (  906): wakingUp
I/InputMethodManagerService(  906): Disable input method client, pid=1268
V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,D/NfcService( 1254): applyRouting -2
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
D/PMS     (  906): acquireWL(42e34ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMS     (  906): acquireWL(42e35490): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/WindowManager(  906): No lock screen! windowToken=null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(42e35490): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): onScreenOn
D/PowerUI ( 1115): closing low battery warning: level=100
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2443): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/NfcService( 1254): applyRouting - 0
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(42e34ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/MtpService( 2443): [MTP][onReceive]-
,D/AutoSetting( 1381): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1254): applyRouting -2
D/PMS     (  906): acquireWL(42e3b890): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PMS     (  906): releaseWL(42e3b890): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/AutoSetting( 1381): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 4220): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4220): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4220): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4220): Cust_ConnectToPC   : spcsc>false
D/        ( 4220): Cust_ConnectToPC   : IPT>true
,D/        ( 4220): Cust_ConnectToPC   : Singel_USB>false
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20364 delay=15s
,W/Settings( 4220): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4220): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4220): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4220): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/ClockThread( 1115): stop update clock
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/PSReceiver( 4220): onReceive:android.intent.action.USER_PRESENT
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): BG scan when screen On
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): Match BG scan, scan!
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
D/WifiNative-wlan0(  906):    returned true
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,I/SmartNS_PSService( 4220): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4220): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4220):  defaultType:0
W/ContextImpl( 4220): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,V/SRS_Proc(  373): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  906): updateScreenOn: false
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4522 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOn: false
D/PMS     (  906): acquireWL(42e50408): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
,D/PMS     (  906): releaseWL(42e50408): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): onScreenOn: 1454714875388
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1777): onScreenOn: 1454714875388
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426c3eb0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426c3eb0, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42bbd5e8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
,I/FeedHostManager( 1268): [onPause]
,I/FeedProviderManager( 1268): onPause
I/SocialFeedProvider( 1268): +onPause
,I/SocialFeedProvider( 1268): -onPause
,I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42242a80
D/PMS     (  906): acquireWL(42e521c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20364 mDataStallAlarmIntent=PendingIntent{42a19908: PendingIntentRecord{4291b578 android broadcastIntent}}
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): acquireWL(42e58780): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(42e521c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/ContextImpl( 4522): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4522): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(42e5b1a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4522 1000 null
,D/SmartSyncUtils( 4522): getMobilePolicyEnabled, result = true
D/PMS     (  906): releaseWL(42e5b1a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  906): killProcessQuiet, pid=4114
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4114:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4114
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:Off
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,I/SensorManager(  906): mEventCount = 900
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
V/SRS_Proc(  373): ParamSet string: screen_state=off
,D/NetworkPolicy(  906): updateScreenOn: false
,W/ContextImpl( 4522): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4522): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4522): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4522): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42bbd5e8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42bbd5e8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42bbd5e8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42bbd5e8
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42c23d20 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42c23d20 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/AutoSetting( 1381): service - mHandler: cancel location update
,D/AutoSetting( 1381): service -           changes count: 0
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(42e7c1e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1777): onScreenOff
D/PMS     (  906): releaseWL(42e7c1e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42e58780): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1159): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1159): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1159): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1159): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1159): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1159): Add randomness: count=14 entropy=7
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: DISCONNECTED -> INACTIVE
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0,
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000022360987
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000113976294
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000113976306
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000113976316
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42b91830 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@42b91830 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@42b91830 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 22360987, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 113976294, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 113976306, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 113976316, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/AutoSetting( 1505): service - handleMessage() stop self,
,D/AutoSetting( 1505): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4297
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1505): service - handleMessage() quit looper
I/ActivityManager(  906): Killing 4297:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4297
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42dc7530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=116592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42dc7530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=3960
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3960:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3960
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=15 entropy=8
D/wpa_supplicant( 1159): Add randomness: count=16 entropy=9
D/wpa_supplicant( 1159): Add randomness: count=17 entropy=10
D/wpa_supplicant( 1159): Add randomness: count=18 entropy=11
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=19 entropy=12
D/wpa_supplicant( 1159): Add randomness: count=20 entropy=13
D/wpa_supplicant( 1159): Add randomness: count=21 entropy=14
D/wpa_supplicant( 1159): Add randomness: count=22 entropy=15
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000131384925
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000131384951
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000131384962
,I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000131384971
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 131384925, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 131384951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 131384962, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 131384971, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/PMS     (  906): acquireWL(4259d608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end,
,D/UsbnetService(  906): BroadcastReceiver::onReceive+,
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4259d608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42b2e7e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42aa3db0: PendingIntentRecord{42aa3e58 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141879, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4294f1b0: PendingIntentRecord{4299d2d8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142763, Int=0
,D/AutoSetting( 1381): service - handleMessage() stop self
,D/AutoSetting( 1381): service - onDestroy() END
,D/AutoSetting( 1381): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4324
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4324:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4324
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
,D/PMS     (  906): acquireWL(426a3390): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =854b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  906): releaseWL(42b2e7e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  906): acquireWL(426a9908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/PMS     (  906): releaseWL(426a9908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): releaseWL(426a3390): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=23 entropy=16
D/wpa_supplicant( 1159): Add randomness: count=24 entropy=17
D/wpa_supplicant( 1159): Add randomness: count=25 entropy=18
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=26 entropy=19
D/wpa_supplicant( 1159): Add randomness: count=27 entropy=20
D/wpa_supplicant( 1159): Add randomness: count=28 entropy=21
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
,I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000148785189
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000131384951
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000148785215
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000148785226
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 148785189, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 131384951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 148785215, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 148785226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList,
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available,
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=29 entropy=22
D/wpa_supplicant( 1159): Add randomness: count=30 entropy=23
D/wpa_supplicant( 1159): Add randomness: count=31 entropy=24
D/wpa_supplicant( 1159): Add randomness: count=32 entropy=25
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=33 entropy=26
D/wpa_supplicant( 1159): Add randomness: count=34 entropy=27
D/wpa_supplicant( 1159): Add randomness: count=35 entropy=28
D/wpa_supplicant( 1159): Add randomness: count=36 entropy=29
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 la,st_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (518) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000166222370
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000166222396
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000166222408
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1159): freq=2462
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000166222416
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC0039325
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 166222370, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 166222396, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 166222408, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 166222416, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
,D/PMS     (  906): acquireWL(42ad7328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PMS     (  906): releaseWL(42ad7328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42c674e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4298e038: PendingIntentRecord{42d03670 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174702, Int=0
,D/PMS     (  906): releaseWL(42c674e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  906): acquireWL(42c9f7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=176592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c9f7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=37 entropy=30
D/wpa_supplicant( 1159): Add randomness: count=38 entropy=31
D/wpa_supplicant( 1159): Add randomness: count=39 entropy=32
D/wpa_supplicant( 1159): Add randomness: count=40 entropy=33
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_us,ed=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=41 entropy=34
D/wpa_supplicant( 1159): Add randomness: count=42 entropy=35
D/wpa_supplicant( 1159): Add randomness: count=43 entropy=36
D/wpa_supplicant( 1159): Add randomness: count=44 entropy=37
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (518) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000166222370
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000183645103
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000183645114
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1159): freq=2462
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000183645122
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC0039325
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 166222370, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 183645103, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 183645114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 183645122, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42ce8c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42ce8c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=45 entropy=38
D/wpa_supplicant( 1159): Add randomness: count=46 entropy=39
D/wpa_supplicant( 1159): Add randomness: count=47 entropy=40
D/wpa_supplicant( 1159): Add randomness: count=48 entropy=41
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_us,ed=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=49 entropy=42
D/wpa_supplicant( 1159): Add randomness: count=50 entropy=43
D/wpa_supplicant( 1159): Add randomness: count=51 entropy=44
D/wpa_supplicant( 1159): Add randomness: count=52 entropy=45
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (518) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000201075269
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000201075296
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000201075306
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1159): freq=2462
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000201075315
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC0039325
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 201075269, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 201075296, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 201075306, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 201075315, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=53 entropy=46
D/wpa_supplicant( 1159): Add randomness: count=54 entropy=47
D/wpa_supplicant( 1159): Add randomness: count=55 entropy=48
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=56 entropy=49
D/wpa_supplicant( 1159): Add randomness: count=57 entropy=50
D/wpa_supplicant( 1159): Add randomness: count=58 entropy=51
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (518) for get BSS: id=0,
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000218501215
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000218501241
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000218501252,
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1159): freq=2462
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000201075315
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC0039325
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000),
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 218501215, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 218501241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 218501252, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 201075315, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e527f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42e527f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=59 entropy=52
D/wpa_supplicant( 1159): Add randomness: count=60 entropy=53
D/wpa_supplicant( 1159): Add randomness: count=61 entropy=54
D/wpa_supplicant( 1159): Add randomness: count=62 entropy=55
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=63 entropy=56
D/wpa_supplicant( 1159): Add randomness: count=64 entropy=57
,D/wpa_supplicant( 1159): Add randomness: count=65 entropy=58
D/wpa_supplicant( 1159): Add randomness: count=66 entropy=59
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
,W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000235905124
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000235905163
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000235905173
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000235905151
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 235905124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 235905163, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 235905173, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 235905151, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults,
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42cbda10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=236591, Int=0,
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42cbda10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(42c55550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end,
D/PMS     (  906): releaseWL(42c55550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=67 entropy=60
D/wpa_supplicant( 1159): Add randomness: count=68 entropy=61
D/wpa_supplicant( 1159): Add randomness: count=69 entropy=62
D/wpa_supplicant( 1159): Add randomness: count=70 entropy=63
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=71 entropy=64
D/wpa_supplicant( 1159): Add randomness: count=72 entropy=65
D/wpa_supplicant( 1159): Add randomness: count=73 entropy=66
D/wpa_supplicant( 1159): Add randomness: count=74 entropy=67
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000253315119
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000253315156
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3,
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000253315166
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55,
I/wpa_supplicant( 1159): tsf=0000000253315145
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 253315119, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 253315156, distance: ?(cm), distanceSd: ?(cm),
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 253315166, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 253315145, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=75 entropy=68
D/wpa_supplicant( 1159): Add randomness: count=76 entropy=69
D/wpa_supplicant( 1159): Add randomness: count=77 entropy=70
D/wpa_supplicant( 1159): Add randomness: count=78 entropy=71
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=79 entropy=72
D/wpa_supplicant( 1159): Add randomness: count=80 entropy=73
D/wpa_supplicant( 1159): Add randomness: count=81 entropy=74
D/wpa_supplicant( 1159): Add randomness: count=82 entropy=75
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000270740967
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000270741004
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000270741014
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000270740994
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 270740967, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 270741004, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 270741014, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 270740994, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=83 entropy=76
D/wpa_supplicant( 1159): Add randomness: count=84 entropy=77
D/wpa_supplicant( 1159): Add randomness: count=85 entropy=78
D/wpa_supplicant( 1159): Add randomness: count=86 entropy=79
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=87 entropy=80
D/wpa_supplicant( 1159): Add randomness: count=88 entropy=81
D/wpa_supplicant( 1159): Add randomness: count=89 entropy=82
D/wpa_supplicant( 1159): Add randomness: count=90 entropy=83
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000288155506
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000288155543
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000288155553
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000288155532
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 288155506, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 288155543, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 288155553, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 288155532, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d8db58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(42d8db58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4522): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4220): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4220): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4220): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4220): Cust_ConnectToPC   : spcsc>false
,D/        ( 4220): Cust_ConnectToPC   : IPT>true
,D/        ( 4220): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4220): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 4220): Index of the first 1 = -1
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
W/ContextImpl( 4220): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4220): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4220): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4220): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4220): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4220): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  906): acquireWL(42e48bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=296592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e48bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=91 entropy=84
D/wpa_supplicant( 1159): Add randomness: count=92 entropy=85
D/wpa_supplicant( 1159): Add randomness: count=93 entropy=86
D/wpa_supplicant( 1159): Add randomness: count=94 entropy=87
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=95 entropy=88
D/wpa_supplicant( 1159): Add randomness: count=96 entropy=89
D/wpa_supplicant( 1159): Add randomness: count=97 entropy=90
D/wpa_supplicant( 1159): Add randomness: count=98 entropy=91
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000305575283
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000305575319
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000305575329
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000305575308
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 305575283, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 305575319, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 305575329, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 305575308, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42ccf148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42ccf148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=99 entropy=92
D/wpa_supplicant( 1159): Add randomness: count=100 entropy=93
D/wpa_supplicant( 1159): Add randomness: count=101 entropy=94
D/wpa_supplicant( 1159): Add randomness: count=102 entropy=95
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=,4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=103 entropy=96
D/wpa_supplicant( 1159): Add randomness: count=104 entropy=97
D/wpa_supplicant( 1159): Add randomness: count=105 entropy=98
D/wpa_supplicant( 1159): Add randomness: count=106 entropy=99
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000322954657
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000322954694
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000322954704
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000322954684
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 322954657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 322954694, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 322954704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 322954684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available,
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes),
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=107 entropy=100
D/wpa_supplicant( 1159): Add randomness: count=108 entropy=101
D/wpa_supplicant( 1159): Add randomness: count=109 entropy=102
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=110 entropy=103
D/wpa_supplicant( 1159): Add randomness: count=111 entropy=104
D/wpa_supplicant( 1159): Add randomness: count=112 entropy=105
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supp,licant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000340381801
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000340381827
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000340381838
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000322954684
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 340381801, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 340381827, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 340381838, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 322954684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42daab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42daab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(42dabbc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=356591, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42dabbc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=113 entropy=106
D/wpa_supplicant( 1159): Add randomness: count=114 entropy=107
D/wpa_supplicant( 1159): Add randomness: count=115 entropy=108
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=116 entropy=109
D/wpa_supplicant( 1159): Add randomness: count=117 entropy=110
D/wpa_supplicant( 1159): Add randomness: count=118 entropy=111
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000357764924
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000357764950
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000357764961
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 357764924, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 357764950, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 357764961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1359): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1359): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1359): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1359): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1359): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1359): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1359): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1359): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/PlayEventLogger( 4161): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4161): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4161): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4161): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4161): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4161): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4161): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4161): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{42226f00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 12 2 12
,D/libc    ( 4161): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4161): [NET] getaddrinfo-,err=8
D/libc    ( 4161): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4161): [NET] getaddrinfo-, 1
D/libc    ( 4161): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =468c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4161): [NET] getaddrinfo_proxy-, success
I/global  ( 4161): call createSocket() return a new socket.
D/libc    ( 4161): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4161): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4161): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4161): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(42e868c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(42e868c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=119 entropy=112
D/wpa_supplicant( 1159): Add randomness: count=120 entropy=113
D/wpa_supplicant( 1159): Add randomness: count=121 entropy=114
D/wpa_supplicant( 1159): Add randomness: count=122 entropy=115
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1159): BSS: last_sca,n_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=123 entropy=116
D/wpa_supplicant( 1159): Add randomness: count=124 entropy=117
D/wpa_supplicant( 1159): Add randomness: count=125 entropy=118
D/wpa_supplicant( 1159): Add randomness: count=126 entropy=119
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (518) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000375205361
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g,
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000375205386
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000375205397
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1159): freq=2462
I/wpa_supplicant( 1159): level=-91
I/wpa_supplicant( 1159): tsf=0000000375205406
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1159): ssid=UPC0039325
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 375205361, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 375205386, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 375205397, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 375205406, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=127 entropy=120
D/wpa_supplicant( 1159): Add randomness: count=128 entropy=121
D/wpa_supplicant( 1159): Add randomness: count=129 entropy=122
D/wpa_supplicant( 1159): Add randomness: count=130 entropy=123
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1159): BSS: last_sca,n_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=131 entropy=124
D/wpa_supplicant( 1159): Add randomness: count=132 entropy=125
D/wpa_supplicant( 1159): Add randomness: count=133 entropy=126
D/wpa_supplicant( 1159): Add randomness: count=134 entropy=127
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (518) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000392611056
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000392611082
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000392611093
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1159): freq=2462
I/wpa_supplicant( 1159): level=-91
I/wpa_supplicant( 1159): tsf=0000000392611101
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC0039325
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateM,achine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 392611056, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 392611082, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 392611093, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 392611101, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=135 entropy=128
D/wpa_supplicant( 1159): Add randomness: count=136 entropy=129
D/wpa_supplicant( 1159): Add randomness: count=137 entropy=130
D/wpa_supplicant( 1159): Add randomness: count=138 entropy=131
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1159): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1159): BSS: last_sca,n_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=139 entropy=132
D/wpa_supplicant( 1159): Add randomness: count=140 entropy=133
D/wpa_supplicant( 1159): Add randomness: count=141 entropy=134
D/wpa_supplicant( 1159): Add randomness: count=142 entropy=135
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (518) for get BSS: id=0,
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000410025151
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000410025177
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====,
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000410025188
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1159): freq=2462
I/wpa_supplicant( 1159): level=-91
I/wpa_supplicant( 1159): tsf=0000000410025197
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC0039325
I/wpa_supplicant( 1159): ####,
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 410025151, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 410025177, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 410025188, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 410025197, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42ed4518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=416592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ed4518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=143 entropy=136
D/wpa_supplicant( 1159): Add randomness: count=144 entropy=137
D/wpa_supplicant( 1159): Add randomness: count=145 entropy=138
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=146 entropy=139
D/wpa_supplicant( 1159): Add randomness: count=147 entropy=140
D/wpa_supplicant( 1159): Add randomness: count=148 entropy=141
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (518) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000427425267
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000427425295
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-72
I/wpa_supplicant( 1159): tsf=0000000427425306
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1159): freq=2462
I/wpa_supplicant( 1159): level=-91
I/wpa_supplicant( 1159): tsf=0000000410025197
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC0039325
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 427425267, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 427425295, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 427425306, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 410025197, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42eee0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(42eee0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=149 entropy=142
D/wpa_supplicant( 1159): Add randomness: count=150 entropy=143
D/wpa_supplicant( 1159): Add randomness: count=151 entropy=144
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=152 entropy=145
D/wpa_supplicant( 1159): Add randomness: count=153 entropy=146
D/wpa_supplicant( 1159): Add randomness: count=154 entropy=147
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000444824979
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000444825005
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-72
I/wpa_supplicant( 1159): tsf=0000000444825016
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 444824979, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 444825005, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 444825016, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=155 entropy=148
D/wpa_supplicant( 1159): Add randomness: count=156 entropy=149
D/wpa_supplicant( 1159): Add randomness: count=157 entropy=150
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=158 entropy=151
D/wpa_supplicant( 1159): Add randomness: count=159 entropy=152
D/wpa_supplicant( 1159): Add randomness: count=160 entropy=153
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000462252007
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000462252033
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-73
I/wpa_supplicant( 1159): tsf=0000000462252044
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 462252007, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 462252033, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 462252044, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42f1d8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,D/PMS     (  906): releaseWL(42f1d8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42efd350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=476592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42efd350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=161 entropy=154
D/wpa_supplicant( 1159): Add randomness: count=162 entropy=155
D/wpa_supplicant( 1159): Add randomness: count=163 entropy=156
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=164 entropy=157
D/wpa_supplicant( 1159): Add randomness: count=165 entropy=158
D/wpa_supplicant( 1159): Add randomness: count=166 entropy=159
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000479654829
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000479654855
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-73
I/wpa_supplicant( 1159): tsf=0000000479654866
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 479654829, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 479654855, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 479654866, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42dc9198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42dc9198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=167 entropy=160
D/wpa_supplicant( 1159): Add randomness: count=168 entropy=161
D/wpa_supplicant( 1159): Add randomness: count=169 entropy=162
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=170 entropy=163
D/wpa_supplicant( 1159): Add randomness: count=171 entropy=164
D/wpa_supplicant( 1159): Add randomness: count=172 entropy=165
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000496762280
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000496762305
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000496762317
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 496762280, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 496762305, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 496762317, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=173 entropy=166
D/wpa_supplicant( 1159): Add randomness: count=174 entropy=167
D/wpa_supplicant( 1159): Add randomness: count=175 entropy=168
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=176 entropy=169
D/wpa_supplicant( 1159): Add randomness: count=177 entropy=170
D/wpa_supplicant( 1159): Add randomness: count=178 entropy=171
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000514162242
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000514162269
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000514162280
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 514162242, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 514162269, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 514162280, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=179 entropy=172
D/wpa_supplicant( 1159): Add randomness: count=180 entropy=173
D/wpa_supplicant( 1159): Add randomness: count=181 entropy=174
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=182 entropy=175
D/wpa_supplicant( 1159): Add randomness: count=183 entropy=176
D/wpa_supplicant( 1159): Add randomness: count=184 entropy=177
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000531585514
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000531585540
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000531585551
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 531585514, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 531585540, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 531585551, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42b460a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=536592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42b460a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=185 entropy=178
D/wpa_supplicant( 1159): Add randomness: count=186 entropy=179
D/wpa_supplicant( 1159): Add randomness: count=187 entropy=180
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=188 entropy=181
D/wpa_supplicant( 1159): Add randomness: count=189 entropy=182
D/wpa_supplicant( 1159): Add randomness: count=190 entropy=183
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000548985295
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000548985321
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
,I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000548985332
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 548985295, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 548985321, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 548985332, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42b20180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42b20180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=191 entropy=184
D/wpa_supplicant( 1159): Add randomness: count=192 entropy=185
D/wpa_supplicant( 1159): Add randomness: count=193 entropy=186
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=194 entropy=187
D/wpa_supplicant( 1159): Add randomness: count=195 entropy=188
D/wpa_supplicant( 1159): Add randomness: count=196 entropy=189
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000566352540
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000566352565
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000566352578
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 566352540, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 566352565, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 566352578, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=197 entropy=190
D/wpa_supplicant( 1159): Add randomness: count=198 entropy=191
D/wpa_supplicant( 1159): Add randomness: count=199 entropy=192
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=200 entropy=193
D/wpa_supplicant( 1159): Add randomness: count=201 entropy=194
D/wpa_supplicant( 1159): Add randomness: count=202 entropy=195
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000583692472
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000583692497
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000583692509
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 583692472, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 583692497, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 583692509, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42be3638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=596591, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42be3638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=203 entropy=196
D/wpa_supplicant( 1159): Add randomness: count=204 entropy=197
D/wpa_supplicant( 1159): Add randomness: count=205 entropy=198
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=206 entropy=199
D/wpa_supplicant( 1159): Add randomness: count=207 entropy=200
D/wpa_supplicant( 1159): Add randomness: count=208 entropy=201
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000601065279
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
,I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000601065306
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000601065317
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 601065279, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 601065306, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 601065317, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42cb6110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42cb6110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=209 entropy=202
D/wpa_supplicant( 1159): Add randomness: count=210 entropy=203
D/wpa_supplicant( 1159): Add randomness: count=211 entropy=204
D/wpa_supplicant( 1159): Add randomness: count=212 entropy=205
D/wpa_supplicant( 1159): Add randomness: count=213 entropy=206
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 4: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/w,pa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=214 entropy=207
D/wpa_supplicant( 1159): Add randomness: count=215 entropy=208
D/wpa_supplicant( 1159): Add randomness: count=216 entropy=209
D/wpa_supplicant( 1159): Add randomness: count=217 entropy=210
D/wpa_supplicant( 1159): Add randomness: count=218 entropy=211
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (619) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000618202360
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000618202399
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000618202409
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=7
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000618202386
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=8
I/wpa_supplicant( 1159): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-87
I/wpa_supplicant( 1159): tsf=0000000618202418
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=UPC243894600
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 618202360, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 618202399, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 618202409, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 618202386, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 618202418, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
,D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=219 entropy=212
D/wpa_supplicant( 1159): Add randomness: count=220 entropy=213
D/wpa_supplicant( 1159): Add randomness: count=221 entropy=214
D/wpa_supplicant( 1159): Add randomness: count=222 entropy=215
D/wpa_supplicant( 1159): Add randomness: count=223 entropy=216
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 4: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplic,ant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=224 entropy=217
D/wpa_supplicant( 1159): Add randomness: count=225 entropy=218
D/wpa_supplicant( 1159): Add randomness: count=226 entropy=219
D/wpa_supplicant( 1159): Add randomness: count=227 entropy=220
D/wpa_supplicant( 1159): Add randomness: count=228 entropy=221
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (619) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000635585447
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000635585484
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000635585494
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ss,id=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=7
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000635585473
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=8
I/wpa_supplicant( 1159): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-87
I/wpa_supplicant( 1159): tsf=0000000635585503
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=UPC243894600
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 635585447, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 635585484, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 635585494, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 635585473, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 635585503, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=229 entropy=222
D/wpa_supplicant( 1159): Add randomness: count=230 entropy=223
D/wpa_supplicant( 1159): Add randomness: count=231 entropy=224
D/wpa_supplicant( 1159): Add randomness: count=232 entropy=225
D/wpa_supplicant( 1159): Add randomness: count=233 entropy=226
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 4: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplic,ant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1159): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-87
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=234 entropy=227
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1159): Add randomness: count=235 entropy=228
D/wpa_supplicant( 1159): Add randomness: count=236 entropy=229
D/wpa_supplicant( 1159): Add randomness: count=237 entropy=230
D/wpa_supplicant( 1159): Add randomness: count=238 entropy=231
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (619) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000653010764
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000653010800
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000653010810
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ss,id=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=7
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000653010790
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=8
I/wpa_supplicant( 1159): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-87
I/wpa_supplicant( 1159): tsf=0000000653010821
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=UPC243894600
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 653010764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 653010800, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 653010810, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 653010790, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 653010821, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42c7ec90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=656591, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c7ec90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-69
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=239 entropy=232
D/wpa_supplicant( 1159): Add randomness: count=240 entropy=233
D/wpa_supplicant( 1159): Add randomness: count=241 entropy=234
D/wpa_supplicant( 1159): Add randomness: count=242 entropy=235
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-69
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=243 entropy=236
D/wpa_supplicant( 1159): Add randomness: count=244 entropy=237
D/wpa_supplicant( 1159): Add randomness: count=245 entropy=238
D/wpa_supplicant( 1159): Add randomness: count=246 entropy=239
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (619) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000670445574
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000670445610
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-69
I/wpa_supplicant( 1159): tsf=0000000670445620
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=7
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000670445600
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=8
I/wpa_supplicant( 1159): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-87
I/wpa_supplicant( 1159): tsf=0000000653010821
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=UPC243894600
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 670445574, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 670445610, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -69, frequency: 2412, timestamp: 670445620, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 670445600, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 653010821, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 5 to mScanResults,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  82, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 13 [-69], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42dad460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42dad460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/Process (  906): killProcessQuiet, pid=4197,
,I/ActivityManager(  906): Killing 4197:com.google.android.apps.plus/u0a160 (adj 15): empty #17,
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4197
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=247 entropy=240
D/wpa_supplicant( 1159): Add randomness: count=248 entropy=241
D/wpa_supplicant( 1159): Add randomness: count=249 entropy=242
D/wpa_supplicant( 1159): Add randomness: count=250 entropy=243
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=251 entropy=244
D/wpa_supplicant( 1159): Add randomness: count=252 entropy=245
D/wpa_supplicant( 1159): Add randomness: count=253 entropy=246
D/wpa_supplicant( 1159): Add randomness: count=254 entropy=247
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000687881624
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000687881660
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-81
I/wpa_supplicant( 1159): tsf=0000000687881670
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=7
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000687881650
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 687881624, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 687881660, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 687881670, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 687881650, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=255 entropy=248
D/wpa_supplicant( 1159): Add randomness: count=256 entropy=249
D/wpa_supplicant( 1159): Add randomness: count=257 entropy=250
D/wpa_supplicant( 1159): Add randomness: count=258 entropy=251
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=259 entropy=252
D/wpa_supplicant( 1159): Add randomness: count=260 entropy=253
D/wpa_supplicant( 1159): Add randomness: count=261 entropy=254
D/wpa_supplicant( 1159): Add randomness: count=262 entropy=255
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000705255255
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000705255292
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-76
I/wpa_supplicant( 1159): tsf=0000000705255302
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=7
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000705255281
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 705255255, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 705255292, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 705255302, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 705255281, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e71240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=716591, Int=0
,D/PMS     (  906): releaseWL(42e71240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=263 entropy=256
D/wpa_supplicant( 1159): Add randomness: count=264 entropy=257
D/wpa_supplicant( 1159): Add randomness: count=265 entropy=258
D/wpa_supplicant( 1159): Add randomness: count=266 entropy=259
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=267 entropy=260
D/wpa_supplicant( 1159): Add randomness: count=268 entropy=261
D/wpa_supplicant( 1159): Add randomness: count=269 entropy=262
D/wpa_supplicant( 1159): Add randomness: count=270 entropy=263
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000705255255
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000722675028
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000722675039
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=7
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000722675018
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 705255255, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 722675028, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 722675039, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 722675018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42cb7f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(42cb7f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=271 entropy=264
D/wpa_supplicant( 1159): Add randomness: count=272 entropy=265
D/wpa_supplicant( 1159): Add randomness: count=273 entropy=266
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=274 entropy=267
D/wpa_supplicant( 1159): Add randomness: count=275 entropy=268
D/wpa_supplicant( 1159): Add randomness: count=276 entro,py=269
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000739782281
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000739782307
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000739782320
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=7
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000722675018
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 739782281, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 739782307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 739782320, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 722675018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=277 entropy=270
D/wpa_supplicant( 1159): Add randomness: count=278 entropy=271
D/wpa_supplicant( 1159): Add randomness: count=279 entropy=272
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=280 entropy=273
D/wpa_supplicant( 1159): Add randomness: count=281 entropy=274
D/wpa_supplicant( 1159): Add randomness: count=282 entro,py=275
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000757167486
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000757167512
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000757167523
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 757167486, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 757167512, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 757167523, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=283 entropy=276
D/wpa_supplicant( 1159): Add randomness: count=284 entropy=277
D/wpa_supplicant( 1159): Add randomness: count=285 entropy=278
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=286 entropy=279
D/wpa_supplicant( 1159): Add randomness: count=287 entropy=280
D/wpa_supplicant( 1159): Add randomness: count=288 entro,py=281
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000774605100
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000774605127
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-83
I/wpa_supplicant( 1159): tsf=0000000774605138
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 774605100, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 774605127, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 774605138, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e89878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=776592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e89878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=289 entropy=282
D/wpa_supplicant( 1159): Add randomness: count=290 entropy=283
D/wpa_supplicant( 1159): Add randomness: count=291 entropy=284
D/wpa_supplicant( 1159): Add randomness: count=292 entropy=285
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=293 entropy=286
D/wpa_supplicant( 1159): Add randomness: count=294 entropy=287
D/wpa_supplicant( 1159): Add randomness: count=295 entropy=288
D/wpa_supplicant( 1159): Add randomness: count=296 entropy=289
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
,I/wpa_supplicant( 1159): tsf=0000000791872158
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000791872195
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-83
I/wpa_supplicant( 1159): tsf=0000000791872205
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=9
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
,I/wpa_supplicant( 1159): tsf=0000000791872183
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 791872158, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 791872195, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 791872205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 791872183, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42cd03d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42cd03d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42ca4628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  906): sending alarm PendingIntent{42389900: PendingIntentRecord{42a12240 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784880, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4233e160: PendingIntentRecord{42a739c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=800597, Int=0
D/ConnectivityService(  906): Done.
D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4565 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42a9d568: PendingIntentRecord{42a5e620 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454714984763, Int=10800000
,D/PMS     (  906): acquireWL(42cad890): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42ed3538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42ca4628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(42cad890): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42ed3538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4565/10047)
,D/Process (  906): killProcessQuiet, pid=3450
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3450:com.htc.task/u0a70 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3450
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=297 entropy=290
D/wpa_supplicant( 1159): Add randomness: count=298 entropy=291
D/wpa_supplicant( 1159): Add randomness: count=299 entropy=292
D/wpa_supplicant( 1159): Add randomness: count=300 entropy=293
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=301 entropy=294
D/wpa_supplicant( 1159): Add randomness: count=302 entropy=295
D/wpa_supplicant( 1159): Add randomness: count=303 entropy=296
D/wpa_supplicant( 1159): Add randomness: count=304 entropy=297
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000791872158
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000809305377
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-76
I/wpa_supplicant( 1159): tsf=0000000809305387
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=9
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000000809305367
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 791872158, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 809305377, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 809305387, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 809305367, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=305 entropy=298
D/wpa_supplicant( 1159): Add randomness: count=306 entropy=299
D/wpa_supplicant( 1159): Add randomness: count=307 entropy=300
D/wpa_supplicant( 1159): Add randomness: count=308 entropy=301
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
,D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=309 entropy=302
D/wpa_supplicant( 1159): Add randomness: count=310 entropy=303
D/wpa_supplicant( 1159): Add randomness: count=311 entropy=304
D/wpa_supplicant( 1159): Add randomness: count=312 entropy=305
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000826740822
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000826740859
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000826740869
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=9
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000000826740848
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 826740822, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 826740859, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 826740869, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 826740848, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000),
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e623c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=836592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e623c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=313 entropy=306
D/wpa_supplicant( 1159): Add randomness: count=314 entropy=307
D/wpa_supplicant( 1159): Add randomness: count=315 entropy=308
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=316 entropy=309
D/wpa_supplicant( 1159): Add randomness: count=317 entropy=310
D/wpa_supplicant( 1159): Add randomness: count=318 entro,py=311
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000844154949
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000844154975
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000000844154987
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=9
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000000826740848
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 844154949, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 844154975, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 844154987, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 826740848, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d0fc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42d0fc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=319 entropy=312
D/wpa_supplicant( 1159): Add randomness: count=320 entropy=313
D/wpa_supplicant( 1159): Add randomness: count=321 entropy=314
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=322 entropy=315
D/wpa_supplicant( 1159): Add randomness: count=323 entropy=316
D/wpa_supplicant( 1159): Add randomness: count=324 entro,py=317
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000861575067
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000861575093
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000861575104
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 861575067, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 861575093, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 861575104, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter,
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1159): nl80211: Event message available,
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=325 entropy=318
D/wpa_supplicant( 1159): Add randomness: count=326 entropy=319
,D/wpa_supplicant( 1159): Add randomness: count=327 entropy=320
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
,I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=328 entropy=321
D/wpa_supplicant( 1159): Add randomness: count=329 entropy=322
D/wpa_supplicant( 1159): Add randomness: count=330 entropy=323
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000878959710
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
,I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000878959736
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000878959747
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 878959710, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 878959736, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 878959747, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=331 entropy=324
D/wpa_supplicant( 1159): Add randomness: count=332 entropy=325
D/wpa_supplicant( 1159): Add randomness: count=333 entropy=326
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=334 entropy=327
D/wpa_supplicant( 1159): Add randomness: count=335 entropy=328
D/wpa_supplicant( 1159): Add randomness: count=336 entro,py=329
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000896355016
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000896355042
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000000896355053,
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 896355016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 896355042, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 896355053, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d49580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=896591, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d49580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(42d4bde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d4bde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=337 entropy=330
D/wpa_supplicant( 1159): Add randomness: count=338 entropy=331
D/wpa_supplicant( 1159): Add randomness: count=339 entropy=332
D/wpa_supplicant( 1159): Add randomness: count=340 entropy=333
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=341 entropy=334
D/wpa_supplicant( 1159): Add randomness: count=342 entropy=335
D/wpa_supplicant( 1159): Add randomness: count=343 entropy=336
D/wpa_supplicant( 1159): Add randomness: count=344 entropy=337
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000913780713
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000913780750
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-73
I/wpa_supplicant( 1159): tsf=0000000913780760
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=10
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000000913780738
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 913780713, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 913780750, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 913780760, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 913780738, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=345 entropy=338
D/wpa_supplicant( 1159): Add randomness: count=346 entropy=339
D/wpa_supplicant( 1159): Add randomness: count=347 entropy=340
D/wpa_supplicant( 1159): Add randomness: count=348 entropy=341
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=349 entropy=342
D/wpa_supplicant( 1159): Add randomness: count=350 entropy=343
D/wpa_supplicant( 1159): Add randomness: count=351 entropy=344
D/wpa_supplicant( 1159): Add randomness: count=352 entropy=345
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000931185077
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000931185114
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-81
I/wpa_supplicant( 1159): tsf=0000000931185124
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=10
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000000931185103
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 931185077, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 931185114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 931185124, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 931185103, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=353 entropy=346
D/wpa_supplicant( 1159): Add randomness: count=354 entropy=347
D/wpa_supplicant( 1159): Add randomness: count=355 entropy=348
D/wpa_supplicant( 1159): Add randomness: count=356 entropy=349
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=357 entropy=350
D/wpa_supplicant( 1159): Add randomness: count=358 entropy=351
D/wpa_supplicant( 1159): Add randomness: count=359 entropy=352
D/wpa_supplicant( 1159): Add randomness: count=360 entropy=353
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000948611180
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000948611205
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-83
I/wpa_supplicant( 1159): tsf=0000000948611225
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=10
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000000948611216
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 948611180, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 948611205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 948611225, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 948611216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42f35478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=956591, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42f35478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=361 entropy=354
D/wpa_supplicant( 1159): Add randomness: count=362 entropy=355
D/wpa_supplicant( 1159): Add randomness: count=363 entropy=356
D/wpa_supplicant( 1159): Add randomness: count=364 entropy=357
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=365 entropy=358
D/wpa_supplicant( 1159): Add randomness: count=366 entropy=359
D/wpa_supplicant( 1159): Add randomness: count=367 entropy=360
D/wpa_supplicant( 1159): Add randomness: count=368 entropy=361
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000965964360
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000965964388,
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-83
I/wpa_supplicant( 1159): tsf=0000000965964409
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=10
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000000965964399
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 965964360, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 965964388, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 965964409, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 965964399, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42dc82a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42dc82a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=369 entropy=362
D/wpa_supplicant( 1159): Add randomness: count=370 entropy=363
D/wpa_supplicant( 1159): Add randomness: count=371 entropy=364
D/wpa_supplicant( 1159): Add randomness: count=372 entropy=365
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=373 entropy=366
D/wpa_supplicant( 1159): Add randomness: count=374 entropy=367
D/wpa_supplicant( 1159): Add randomness: count=375 entropy=368
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): Add randomness: count=376 entropy=369
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000983405138
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000000983405164
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-76
I/wpa_supplicant( 1159): tsf=0000000983405186
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=10
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000000983405175
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 983405138, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 983405164, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 983405186, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 983405175, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=377 entropy=370
D/wpa_supplicant( 1159): Add randomness: count=378 entropy=371
D/wpa_supplicant( 1159): Add randomness: count=379 entropy=372
D/wpa_supplicant( 1159): Add randomness: count=380 entropy=373
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=381 entropy=374
D/wpa_supplicant( 1159): Add randomness: count=382 entropy=375
D/wpa_supplicant( 1159): Add randomness: count=383 entropy=376
D/wpa_supplicant( 1159): Add randomness: count=384 entropy=377
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001000822020
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001000822047
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000001000822067
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=10
I/wpa_supp,licant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000001000822057
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1000822020, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1000822047, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1000822067, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1000822057, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(429daf78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{422da140: PendingIntentRecord{429a0998 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928586, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42a46520: PendingIntentRecord{42a41a20 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454715705090, Int=900000
,D/PMS     (  906): acquireWL(427d5e68): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1359 10028 null
,V/AlarmManager(  906): sending alarm PendingIntent{429708a0: PendingIntentRecord{42e5ce40 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454715776094, Int=0
,D/PMS     (  906): releaseWL(427d5e68): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): acquireWL(423720c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
,D/PMS     (  906): releaseWL(423720c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4522): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4522): call getInstance()
,D/SmartSyncUtils( 4522): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4522): MY_DEBUG = false
D/PMS     (  906): releaseWL(429daf78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(42ba9638): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4522 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4522): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4522): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 20, nEnd = 23, bNormalRange = true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/dalvikvm-heap(  906): Grow heap (frag case) to 17.730MB for 148516-byte allocation
,D/SmartSyncScreenOnOffTimeReceiver( 4522): [updateNmRange] new USERNIGHT_TIMESTART = 20, new USERNIGHT_TIMEEND = 23
,I/FeedHostManager( 1268): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,W/ContextImpl( 4522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,D/SmartSyncScreenOnOffTimeReceiver( 4522): AlarmOnTime = -1
,I/FeedHostManager( 1268): NightMode begin at 0, end at 7
D/SmartSyncScreenOnOffTimeReceiver( 4522): SettingOnTime = 1454796000000, randomSettingOnTime = 1454793629000
,D/SmartSyncScreenOnOffTimeReceiver( 4522): SettingOffTime = 1454785200000, randomSettingOffTime = 1454785778000
,D/PMS     (  906): acquireWL(42e01c40): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1268 10075 null
D/SmartSyncScreenOnOffTimeReceiver( 4522): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4522): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4522): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(42ba9638): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(42dfaf80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10075}
,I/FeedHostManager( 1268): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1454715776353, BeginTime: 1454713200000, EndTime: 1454738400000
,I/FeedHostManager( 1268): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
V/AlarmManager(  906): sending alarm PendingIntent{4251fe48: PendingIntentRecord{42c559f0 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1454713200000, Int=0
D/PMS     (  906): releaseWL(42e01c40): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  906): acquireWL(42df8c78): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1268 10075 null
D/PMS     (  906): releaseWL(42df8c78): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  906): releaseWL(42dfaf80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(42be9390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1016592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42be9390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=385 entropy=378
D/wpa_supplicant( 1159): Add randomness: count=386 entropy=379
D/wpa_supplicant( 1159): Add randomness: count=387 entropy=380
D/wpa_supplicant( 1159): Add randomness: count=388 entropy=381
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=389 entropy=382
D/wpa_supplicant( 1159): Add randomness: count=390 entropy=383
D/wpa_supplicant( 1159): Add randomness: count=391 entropy=384
D/wpa_supplicant( 1159): Add randomness: count=392 entropy=385
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
,W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001017902111
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001017902136
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000001017902157
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=10
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000001017902146
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
,I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/PMS     (  906): acquireWL(42440088): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/GCM     ( 1359): Message class mow
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1017902111, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1017902136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1017902157, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1017902146, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/PMS     (  906): releaseWL(42440088): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/PMS     (  906): acquireWL(42dfb290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(42dfb290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(42decf38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42decf38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=393 entropy=386
D/wpa_supplicant( 1159): Add randomness: count=394 entropy=387
D/wpa_supplicant( 1159): Add randomness: count=395 entropy=388
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=396 entropy=389
D/wpa_supplicant( 1159): Add randomness: count=397 entropy=390
D/wpa_supplicant( 1159): Add randomness: count=398 entro,py=391
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001035102201
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001035102227
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000001035102238
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=10
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000001017902146
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1035102201, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1035102227, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1035102238, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1017902146, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=399 entropy=392
D/wpa_supplicant( 1159): Add randomness: count=400 entropy=393
D/wpa_supplicant( 1159): Add randomness: count=401 entropy=394
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=402 entropy=395
D/wpa_supplicant( 1159): Add randomness: count=403 entropy=396
D/wpa_supplicant( 1159): Add randomness: count=404 entro,py=397
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001052232630
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001052232657
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-75
I/wpa_supplicant( 1159): tsf=0000001052232668
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1052232630, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1052232657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1052232668, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=405 entropy=398
D/wpa_supplicant( 1159): Add randomness: count=406 entropy=399
D/wpa_supplicant( 1159): Add randomness: count=407 entropy=400
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=408 entropy=401
D/wpa_supplicant( 1159): Add randomness: count=409 entropy=402
D/wpa_supplicant( 1159): Add randomness: count=410 entro,py=403
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001052232630
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001069362566
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001069362578
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1052232630, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1069362566, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1069362578, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42dac568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1076592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42dac568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=411 entropy=404
D/wpa_supplicant( 1159): Add randomness: count=412 entropy=405
D/wpa_supplicant( 1159): Add randomness: count=413 entropy=406
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=414 entropy=407
D/wpa_supplicant( 1159): Add randomness: count=415 entropy=408
D/wpa_supplicant( 1159): Add randomness: count=416 entro,py=409
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
,I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001086765087
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001086765114
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001086765124
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1086765087, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1086765114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1086765124, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/PMS     (  906): acquireWL(42ebd5c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ebd5c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=417 entropy=410
D/wpa_supplicant( 1159): Add randomness: count=418 entropy=411
D/wpa_supplicant( 1159): Add randomness: count=419 entropy=412
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=420 entropy=413
D/wpa_supplicant( 1159): Add randomness: count=421 entropy=414
D/wpa_supplicant( 1159): Add randomness: count=422 entro,py=415
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
,I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  906): getDiscoveryDongleList
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001104184976
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001104185002
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001104185015
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1104184976, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1104185002, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1104185015, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=423 entropy=416
D/wpa_supplicant( 1159): Add randomness: count=424 entropy=417
D/wpa_supplicant( 1159): Add randomness: count=425 entropy=418
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=426 entropy=419
D/wpa_supplicant( 1159): Add randomness: count=427 entropy=420
D/wpa_supplicant( 1159): Add randomness: count=428 entropy=421
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001121571862
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001121571889
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001121571900
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1121571862, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1121571889, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1121571900, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/PMS     (  906): acquireWL(42e476b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1136592, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e476b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=429 entropy=422
D/wpa_supplicant( 1159): Add randomness: count=430 entropy=423
D/wpa_supplicant( 1159): Add randomness: count=431 entropy=424
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=432 entropy=425
D/wpa_supplicant( 1159): Add randomness: count=433 entropy=426
D/wpa_supplicant( 1159): Add randomness: count=434 entro,py=427
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001138985305
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
,I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001138985331
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001138985342
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1138985305, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1138985331, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1138985342, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1,
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42b6c4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42b6c4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=435 entropy=428
D/wpa_supplicant( 1159): Add randomness: count=436 entropy=429
D/wpa_supplicant( 1159): Add randomness: count=437 entropy=430
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=438 entropy=431
D/wpa_supplicant( 1159): Add randomness: count=439 entropy=432
D/wpa_supplicant( 1159): Add randomness: count=440 entro,py=433
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001156102764
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001156102789
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001156102801
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1156102764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1156102789, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1156102801, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=441 entropy=434
D/wpa_supplicant( 1159): Add randomness: count=442 entropy=435
D/wpa_supplicant( 1159): Add randomness: count=443 entropy=436
D/wpa_supplicant( 1159): Add randomness: count=444 entropy=437
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=445 entropy=438
D/wpa_supplicant( 1159): Add randomness: count=446 entropy=439
D/wpa_supplicant( 1159): Add randomness: count=447 entropy=440
D/wpa_supplicant( 1159): Add randomness: count=448 entropy=441
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001173541915
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001173541941
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001173541963
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=11
I/wpa_supp,licant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000001173541951
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1173541915, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1173541941, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1173541963, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1173541951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=449 entropy=442
D/wpa_supplicant( 1159): Add randomness: count=450 entropy=443
D/wpa_supplicant( 1159): Add randomness: count=451 entropy=444
D/wpa_supplicant( 1159): Add randomness: count=452 entropy=445
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=453 entropy=446
D/wpa_supplicant( 1159): Add randomness: count=454 entropy=447
D/wpa_supplicant( 1159): Add randomness: count=455 entropy=448
D/wpa_supplicant( 1159): Add randomness: count=456 entropy=449
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001173541915
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001190955042
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====,
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001190955062
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=11
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000001190955053
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1173541915, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1190955042, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1190955062, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1190955053, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==,
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42ebc2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1196592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ebc2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=457 entropy=450
D/wpa_supplicant( 1159): Add randomness: count=458 entropy=451
D/wpa_supplicant( 1159): Add randomness: count=459 entropy=452
D/wpa_supplicant( 1159): Add randomness: count=460 entropy=453
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
,I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=461 entropy=454
,D/wpa_supplicant( 1159): Add randomness: count=462 entropy=455
D/wpa_supplicant( 1159): Add randomness: count=463 entropy=456
D/wpa_supplicant( 1159): Add randomness: count=464 entropy=457
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
,I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001208365038
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001208365064
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001208365085
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
,I/wpa_supplicant( 1159): id=11
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000001208365075
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1208365038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1208365064, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1208365085, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1208365075, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d02b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d02b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=465 entropy=458
D/wpa_supplicant( 1159): Add randomness: count=466 entropy=459
D/wpa_supplicant( 1159): Add randomness: count=467 entropy=460
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=468 entropy=461
D/wpa_supplicant( 1159): Add randomness: count=469 entropy=462
D/wpa_supplicant( 1159): Add randomness: count=470 entro,py=463
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (490) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001225791285
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55,
I/wpa_supplicant( 1159): tsf=0000001225791311
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001225791322
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=11
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-56
I/wpa_supplicant( 1159): tsf=0000001208365075
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1225791285, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1225791311, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1225791322, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1208365075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter,
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=471 entropy=464
D/wpa_supplicant( 1159): Add randomness: count=472 entropy=465
D/wpa_supplicant( 1159): Add randomness: count=473 entropy=466
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=4,74 entropy=467
D/wpa_supplicant( 1159): Add randomness: count=475 entropy=468
D/wpa_supplicant( 1159): Add randomness: count=476 entropy=469
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001243182498
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001243182524
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001243182536
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1243182498, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1243182524, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1243182536, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d68d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{420ce890: PendingIntentRecord{4296f618 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1256592, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d68d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=477 entropy=470
D/wpa_supplicant( 1159): Add randomness: count=478 entropy=471
D/wpa_supplicant( 1159): Add randomness: count=479 entropy=472
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
,D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=480 entropy=473
D/wpa_supplicant( 1159): Add randomness: count=481 entropy=474
D/wpa_supplicant( 1159): Add randomness: count=482 entropy=475
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001260575173
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001260575198
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700,
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001260575209
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1260575173, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1260575198, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1260575209, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==,
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42de85d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42de85d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=483 entropy=476
D/wpa_supplicant( 1159): Add randomness: count=484 entropy=477
D/wpa_supplicant( 1159): Add randomness: count=485 entropy=478
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=486 entropy=479
D/wpa_supplicant( 1159): Add randomness: count=487 entropy=480
D/wpa_supplicant( 1159): Add randomness: count=488 entro,py=481
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001277722248
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001277722275
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001277722286
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  906): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1277722248, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1277722275, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  906): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1277722286, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==,
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=489 entropy=482
D/wpa_supplicant( 1159): Add randomness: count=490 entropy=483
D/wpa_supplicant( 1159): Add randomness: count=491 entropy=484
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=492 entropy=485
D/wpa_supplicant( 1159): Add randomness: count=493 entropy=486
D/wpa_supplicant( 1159): Add randomness: count=494 entro,py=487
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000001295151849
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-55
I/wpa_supplicant( 1159): tsf=0000001295151876
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2412
,I/wpa_supplicant( 1159): level=-74
I/wpa_supplicant( 1159): tsf=0000001295151886
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1295151849, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1295151876, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1295151886, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4587): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4587): ====startRecUseTime====
D/htc.customization.log.level( 4587):  is 
W/CustomizationLogLevel( 4587): Level value is invalid, use default level 2
D/CustomizationManager( 4587):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4587): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4587): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4587): Parsing tag category name = system
I/CustomizationCIDLoader( 4587): Parsing tag category name = application
I/CustomizationCIDLoader( 4587): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4587): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4587): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4587): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4587): Parsing tag category name = Settings
D/CustomizationManager( 4587):  Read CID file spent 0.155 (s)
D/CustomizationManager( 4587):  All configurations done spent 0.155 (s)
W/HtcNativeFlag( 4587): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4587): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4587): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4587): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4587, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{427faf68 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1865): Unregistering com.test.thalitest
E/acms    ( 1865): Could not unregister removed application com.test.thalitest
D/PMS     (  906): acquireWL(42d6aaa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
W/GeofencerStateMachine( 1434): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): releaseWL(42d6aaa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):   Scheme: "smsto"
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PackageBroadcastService( 2226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/ExternalAccountType( 1329): Unsupported attribute readOnly
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4603 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
F/PackageManager(  906): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  906): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager(  906): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager(  906): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager(  906): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  906): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  906): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  906): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  906): 	at com.android.internal.util.FastXmlSerializer.escapeAndAppendString(FastXmlSerializer.java:145)
F/PackageManager(  906): 	at com.android.internal.util.FastXmlSerializer.attribute(FastXmlSerializer.java:176)
F/PackageManager(  906): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1203)
F/PackageManager(  906): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  906): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  906): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  906): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  906): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  906): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  906): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager(  906): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  906): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager(  906): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager(  906): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager(  906): 	... 14 more
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
I/PackageManager(  906): Failed to clean up mangled file: /data/system/packages-stopped.xml
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1454716071618.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  906): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  906): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  906): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  906): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  906): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 18 more
E/SQLiteDatabase( 2226): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2226): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2226): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2226): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2226): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2226): 	at fyb.d(SourceFile:96)
E/SQLiteDatabase( 2226): 	at fyb.a(SourceFile:220)
E/SQLiteDatabase( 2226): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/SQLiteDatabase( 2226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2226): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2226): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2226): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2226): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2226): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2226): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2226): 	at fyb.d(SourceFile:96)
E/SQLiteOpenHelper( 2226): 	at fyb.a(SourceFile:220)
E/SQLiteOpenHelper( 2226): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/SQLiteOpenHelper( 2226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2226): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2226): Opened metrics.db in read-only mode
E/SQLiteLog( 2226): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
W/dalvikvm( 2226): threadid=30: thread exiting with uncaught exception (group=0x41ca4e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
I/ActivityManager(  906): Delaying start of: ServiceRecord{42c14e28 u0 com.google.android.gms/.wearable.service.WearableControlService}
E/AndroidRuntime( 2226): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2226): Process: com.google.android.gms, PID: 2226
E/AndroidRuntime( 2226): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2226): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2226): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2226): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2226): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2226): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2226): 	at fyb.a(SourceFile:223)
E/AndroidRuntime( 2226): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/AndroidRuntime( 2226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2226): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PeopleContactsSync( 2226): CP2 sync disabled
D/Process ( 2226): killProcess, pid=2226
D/Process ( 2226): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/MultiDex( 4603): install
I/MultiDex( 4603): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
I/MultiDex( 4603): loading existing secondary dex files
I/MultiDex( 4603): load found 1 secondary dex files
I/MultiDex( 4603): install done
I/ProviderInstaller( 4603): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ActivityManager(  906): Recipient 2226
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms (pid 2226) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.games.service.GamesIntentService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
E/SQLiteDatabase( 4603): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4603): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4603): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4603): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4603): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4603): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4603): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4603): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4603): threadid=12: thread exiting with uncaught exception (group=0x41ca4e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4603): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4603): Process: com.google.android.gms.drive, PID: 4603
E/AndroidRuntime( 4603): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4603): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4603): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4603): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4603): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4603): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4603): 	at ctn.run(SourceFile:985)
D/Process (  906): killProcessQuiet, pid=4603
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
W/ActivityManager(  906): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  906): Killing 4603:com.google.android.gms.drive/u0a28 (adj 6): crash
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4626 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4626): install
I/MultiDex( 4626): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4626): loading existing secondary dex files
I/MultiDex( 4626): load found 1 secondary dex files
I/MultiDex( 4626): install done
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ProviderInstaller( 4626): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
E/SharedPreferencesImpl( 1208): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1381): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SQLiteLog( 1381): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1381): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca2fb70
W/[PluginManager]RegisterService( 1381): provider may killed!
W/[PluginManager]RegisterService( 1381): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1381): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1381): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1381): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1381): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1381): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1381): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1381): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1381): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1381): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1381): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1381): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1381): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1381): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1381): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2886): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteLog( 2886): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2886): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x644df270
W/dalvikvm( 2886): threadid=14: thread exiting with uncaught exception (group=0x41ca4e30)
E/AndroidRuntime( 2886): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2886): Process: com.google.android.googlequicksearchbox:search, PID: 2886
E/AndroidRuntime( 2886): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2886): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2886): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2886): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2886): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2886): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2886): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2886): 	at cid.d(PG:186)
E/AndroidRuntime( 2886): 	at clo.g(PG:594)
E/AndroidRuntime( 2886): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2886): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2886): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2886): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2886): 	at clr.tL(PG:827)
E/AndroidRuntime( 2886): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2886): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2886): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2886): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2886): killProcess, pid=2886
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
D/Process ( 2886): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@42167d30 +
I/Prism.WidgetManager( 1268): onLoadItems() +
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2886
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2886) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 20251ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 30251ms
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2886): Died!
D/WifiService(  906): Client connection lost with reason: 4
W/PackageManager(  906): Unable to load service info ResolveInfo{42d50898 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)

```
