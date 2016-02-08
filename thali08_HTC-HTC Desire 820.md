#### Test 58380500055030c_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1508): handler message = 4011
E/HtcModeClient( 1508): Check connection and retry 8 times.
,E/cutils-trace( 4301): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4301): ====startRecUseTime====
D/htc.customization.log.level( 4301):  is 
W/CustomizationLogLevel( 4301): Level value is invalid, use default level 2
D/CustomizationManager( 4301):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4301): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4301): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4301): Parsing tag category name = system
I/CustomizationCIDLoader( 4301): Parsing tag category name = application
I/CustomizationCIDLoader( 4301): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4301): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4301): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4301): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4301): Parsing tag category name = Settings
D/CustomizationManager( 4301):  Read CID file spent 0.100 (s)
D/CustomizationManager( 4301):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 4301): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4301): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4301): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4301): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4301
,V/AlarmManager(  904): sending alarm PendingIntent{424bbac8: PendingIntentRecord{42441398 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=70587, Int=0
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/GAV2    ( 4132): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  904): acquireWL(425c4d50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425c4d50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/CalendarProvider2( 1508): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1508): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(4252aec0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3871 10154 null
,I/ActivityManager(  904): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3871): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3871): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3871, uid=10154, userID:0
,I/MusicLeanback( 3871): Conditions not met for autocaching.
,I/MusicLeanback( 3871): Stop autocaching.
D/PMS     (  904): releaseWL(4252aec0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4321 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4321): Loading default preferences
,W/Resources( 4321): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  904): New client listening to asynchronous messages
,D/SyncApplication( 4321): Overriding preferences with custom values
,D/SyncApplication( 4321): Updating preferences succeeded
E/SyncApplication( 4321): Application created.
D/VolumeInfo( 4321): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 4321): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4321): Found 0 mount point(s)
V/VolumeInfo( 4321): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 4321): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 4321): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 4321): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 4321): getNewCalendarAuthority()...
,D/SyncApplication( 4321): enableAppOperation()+
D/SyncApplication( 4321): enableAppOperation()-
,D/HTCUtilities( 4321): isNeorSinged() + 
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4321, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4321, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4321): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4321): isNeorSinged() return false
,D/CDMountReceiver( 4321): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4321): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1579): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4321): enable CD Auto-mount: true
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
D/HTCUtilities( 4321): enable auto-mount
,D/HTCUtilities( 4321): enable auto-mount
I/ActivityManager(  904): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/MountService(  904): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41be1428 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  904): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  904): Resuming delayed broadcast
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 2 13 4 11
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c00990 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 3852): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3914
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3914:com.htc.sdm/u0a80 (adj 15): empty #17
I/ActivityManager(  904): Delay finish: com.google.android.gms/.playlog.uploader.UploaderAlarmReceiver
,W/Uploader( 2252): No account for auth token provided
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 2252): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2252): [NET] getaddrinfo-,err=8
,D/libc    ( 2252): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2252): [NET] getaddrinfo-, 1
,D/libc    ( 2252): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ed0e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
I/ActivityManager(  904): Recipient 3914
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 79
D/libc    (  365): [NET]res_nsend:resplen=87
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2252): [NET] getaddrinfo_proxy-, success
I/global  ( 2252): call createSocket() return a new socket.
D/libc    ( 2252): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2252): [NET] getaddrinfo-, SUCCESS
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42667cb0 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  904): Resuming delayed broadcast
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    ( 2252): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2252): [NET] getaddrinfo-,err=8
,W/ContextImpl( 4185): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  904): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2252/10028)
W/Uploader( 2252): No account for auth token provided
,I/ActivityManager(  904): Resuming delayed broadcast
,D/ConnectivityService(  904): getAllNetworkInfo called by  (2443/10021)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2252/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2252/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2252/10028)
,I/DownloadManager( 2443): Download 281 starting
D/PMS     (  904): acquireWL(42647eb8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2443 10021 WorkSource{10016}
,D/ConnectivityService(  904): getAllNetworkInfo called by  (2443/10021)
,W/ContextImpl( 4185): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2443/10021)
I/wpa_supplicant( 1158): environment dirty rate=7 [14][1][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2443): Ignoring Content-Length since Transfer-Encoding is also defined
,I/AdsMeasurementBroadcastReceiver( 2252): Reporting settings might have changed, alerting AdsMeasurementService
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2443/10021)
,D/ConnectivityService(  904): getAllNetworkInfo called by  (2443/10021)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/AdsMeasurementBroadcastReceiver( 2252): Unauthorized to start the main service
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall,
,I/ActivityManager(  904): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4352 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=127 rxSum=119} preTxRxSum={txSum=67 rxSum=72}
D/WifiDataStallTracker(  904): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  904): onDataStallAlarm: tag=19430 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=19431 delay=15s
D/PMS     (  904): releaseWL(4211c138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/DownloadManager( 2443): Download 282 starting
D/PMS     (  904): acquireWL(425acbd0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2443 10021 WorkSource{10016}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getAllNetworkInfo called by  (2443/10021)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2443/10021)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/CalendarApplication( 4352): onCreate
D/ProviderChangeReceiver( 4352): ---------------------------------------------------
D/ProviderChangeReceiver( 4352): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 4352): start to updateAlertNotification!
,I/ActivityManager(  904): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4368 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  904): killProcessQuiet, pid=3991
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  904): Killing 3991:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/DownloadManager( 2443): Download 281 finished with status SUCCESS
,I/DownloadManager( 2443): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  904): releaseWL(42647eb8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
I/ActivityManager(  904): Recipient 3991
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 4352): No fired or scheduled alerts
,D/HtcAlertUtils( 4352): -- cancelReminderNotification --
,D/HtcAlertUtils( 4352): broadcastExistReminder!
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2443/10021)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=9 [31][3][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,V/Settings:HtcSettingsApplication( 4368): [4368/4368] onCreate()
W/ContextImpl( 4368): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/DownloadManager( 2443): Download 282 finished with status SUCCESS
,W/ContextImpl( 4185): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
D/PMS     (  904): releaseWL(425acbd0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/UpdateFetcherService( 4185): Update downloaded, starting installation
,I/UpdateFetcherService( 4185): Started installation
,W/ContextImpl( 4185): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4185): Update downloaded, starting installation
,I/UpdateFetcherService( 4185): Started installation
,I/ConfigUpdateInstallReceiver(  904): Not installing, new version is <= current version
,D/Process (  904): killProcessQuiet, pid=3973
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3973:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3973
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  904): mEventCount = 600
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/HABCtrl (  904): TPE algorithm. remove timeout.
,D/HABCtrl (  904): ALG=2, lsvalue=10(0th)->40(1th), last_level=-1, lValue=39->64
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 9 times.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/PackageSettings(  904): Skipping PackageSetting{42218718 com.test.thalitest/10189} due to missing metadata
,D/PMS     (  904): releaseWL(426b0088): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:204, mTXpacketCount:128, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 10 times.
,D/PMS     (  904): acquireWL(425e5948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{41c2ac30: PendingIntentRecord{42575f28 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454970758412, Int=0
,D/PMS     (  904): releaseWL(425e5948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/Finsky  ( 4095): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1395): service - mHandler: update timezone
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/AutoSetting( 1395): service - handleMessage() stop self
,D/AutoSetting( 1395): service - handleMessage() quit looper
,D/AutoSetting( 1395): service - onDestroy() END
,D/Process (  904): killProcessQuiet, pid=3555
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3555:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): service - onCreate()
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1508): service - mHandler: update timezone
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1508): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1508): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1579): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c03250 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 7 3 11
,I/ActivityManager(  904): Recipient 3555
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 11 times.
,I/SensorManager(  904): mEventCount = 750
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=161 rxSum=151} preTxRxSum={txSum=127 rxSum=119}
D/WifiDataStallTracker(  904): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  904): onDataStallAlarm: tag=19431 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=19432 delay=15s
D/PMS     (  904): acquireWL(426b9990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{41fafbd8: PendingIntentRecord{42441398 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88119, Int=0
D/PMS     (  904): releaseWL(426b9990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 12 times.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:209, mTXpacketCount:204, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1508): Don't start project servcice
,D/HtcModeClient( 1508): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1508): connectState: CONNECTION_READY = false
D/SilentMusic( 1508): call stop
,D/HtcModeClient( 1508): close connection
,W/HtcModeClient( 1508): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1508): read the terminate packet, so break
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{423594e8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  904): acquireWL(425af870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=101824, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425af870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1117): now=1454970780056 next=59944
,D/PMS     (  904): acquireWL(425cc890): PARTIAL_WAKE_LOCK  Icing 0x1 2252 10028 null
,D/PMS     (  904): releaseWL(425cc890): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(425fdd70): PARTIAL_WAKE_LOCK  Icing 0x1 2252 10028 null
,D/PMS     (  904): releaseWL(425fdd70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(426f2768): PARTIAL_WAKE_LOCK  Icing 0x1 2252 10028 null
,D/PMS     (  904): releaseWL(426f2768): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42587348): PARTIAL_WAKE_LOCK  Icing 0x1 2252 10028 null
,D/PMS     (  904): releaseWL(42587348): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  904): acquireWL(42695eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
V/AlarmManager(  904): sending alarm PendingIntent{424b7ad0: PendingIntentRecord{42441398 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103124, Int=0
D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=162 rxSum=152} preTxRxSum={txSum=161 rxSum=151}
D/WifiDataStallTracker(  904): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  904): onDataStallAlarm: tag=19432 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=19433 delay=15s
D/PMS     (  904): releaseWL(42695eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42669c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{424bdaf8: PendingIntentRecord{4259da10 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454970765389, Int=563223000
,D/PMS     (  904): acquireWL(4271ab20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2252 10028 null
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4399 uid=10077 gids={50077}
,V/AlarmManager(  904): sending alarm PendingIntent{42367fb0: PendingIntentRecord{423649d0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454970782209, Int=60000
,D/PMS     (  904): releaseWL(42669c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  904): acquireWL(425d5390): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2252 10028 null
,D/PMS     (  904): releaseWL(4271ab20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2252/10028)
,I/CheckinService( 2252): Preparing to send checkin request
,I/EventLogService( 2252): Accumulating logs since 1454970731544
,W/EventLogAggregator( 2252): Unknown tag: install_package_attempt
W/EventLogAggregator( 2252): Unknown tag: snet
,W/EventLogAggregator( 2252): Unknown tag: snet_gcore
,D/SMSBackup( 4399): SMSBackupAgentService started
,D/SMSBackup( 4399): Checking restore status
,D/SMSBackup( 4399): Restore complete
,D/SMSBackup( 4399): cancelCheckAlarm
,D/SMSBackup( 4399): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=2777
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2777:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/GoogleHttpClient( 2252): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2252): Using GMS GoogleHttpClient
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2252/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2252/10028)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2777
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1579): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 2252): awaiting user notification for token
,D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c6edb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 7 2 12
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4413 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4413): install
,I/MultiDex( 4413): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4413): loading existing secondary dex files
,I/MultiDex( 4413): load found 1 secondary dex files
,I/MultiDex( 4413): install done
,I/ProviderInstaller( 4413): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  904): mEventCount = 900
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4413/10028)
,W/Settings( 4413): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4413): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4413): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4413): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4413): Local Branch: 
I/Adreno-EGL( 4413): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4413): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4413):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4413): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4413): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4413): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4413): Local Branch: 
I/Adreno-EGL( 4413): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4413): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4413):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4413): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4413): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4413): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4413): Local Branch: 
I/Adreno-EGL( 4413): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4413): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4413):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2252): Sending checkin request (8888 bytes)
D/libc    ( 2252): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2252): [NET] getaddrinfo-,err=8
D/libc    ( 2252): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2252): [NET] getaddrinfo-, 1
,D/libc    ( 2252): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9884 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2252): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2252): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2252): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  904): acquireWL(426f4108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  904): releaseWL(426f4108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2252/10028)
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2252/10028)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [13][0][0]
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1579): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2252): awaiting user notification for token
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c6f440 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 7 3 12
,I/CheckinTask( 2252): Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,W/GoogleHttpClient( 2252): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2252/10028)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  904): releaseWL(425d5390): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/GCM     ( 1364): GCM config loaded
E/ActivityThread( 2252): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d5a430 that was originally bound here
E/ActivityThread( 2252): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d5a430 that was originally bound here
E/ActivityThread( 2252): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2252): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2252): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2252): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2252): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2252): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2252): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2252): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2252): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2252): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2252): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2252): 	at bks.a(SourceFile:298)
E/ActivityThread( 2252): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2252): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2252): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2252): 	at java.lang.Thread.run(Thread.java:864)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:222, mTXpacketCount:209, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Process (  904): killProcessQuiet, pid=4049
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4049:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4049
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420b35d0
D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
W/PMS     (  904): mWirelessDisplayManager is null
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  904): setLight #0: color=#0
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420b35d0, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4227f048
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@4261ffe8
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 375ms
,W/PnPMgr  (  358): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/PMS     (  904): OOBE c monitor 11
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42818838)
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=1271
D/PMN     (  904): wakingUp
,D/NfcService( 1256): ScreenObserver: OFF
D/NfcService( 1256): applyRouting - 0
V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/NfcService( 1256): applyRouting -2
I/WindowManager(  904): No lock screen! windowToken=null
D/PMN     (  904): onScreenOn
D/PMS     (  904): acquireWL(4281a1b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/PMS     (  904): acquireWL(4281b408): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/MtpService( 2443): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1256): applyRouting - 0
D/PMS     (  904): releaseWL(4281b408): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  904): releaseWL(4281a1b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/MtpService( 2443): [MTP][onReceive]-
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1256): applyRouting -2
,D/AutoSetting( 1395): receiver - intent: android.intent.action.USER_PRESENT
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): acquireWL(4281ff70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  904): releaseWL(4281ff70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
D/AutoSetting( 1395): service - onCreate()
D/TetherSettings( 4154): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4154): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4154): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4154): Cust_ConnectToPC   : spcsc>false
D/        ( 4154): Cust_ConnectToPC   : IPT>true
D/        ( 4154): Cust_ConnectToPC   : Singel_USB>false
,D/AutoSetting( 1395): service - AddressCache: using context: com.htc.Weather
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=19434 delay=15s
D/AutoSetting( 1395): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ClockThread( 1117): stop update clock
W/Settings( 4154): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/LocationManagerService(  904): request 424ce970 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): SET_SCREEN_ON:On
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
E/SmartNS_Utility( 4154): hasRemovableStorageSlot: true
D/WifiNative-wlan0(  904):    returned true
D/SmartNS_Utility( 4154): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4154): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,I/PSReceiver( 4154): onReceive:android.intent.action.USER_PRESENT
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
W/ContextImpl( 4154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
I/SmartNS_PSService( 4154): onReceive:android.intent.action.USER_PRESENT
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/Settings( 4154): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4154):  defaultType:0
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  904): updateScreenOn: false
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4443 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1847): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1847): onScreenOn: 1454970789818
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1847): onScreenOn: 1454970789818
D/PMS     (  904): acquireWL(42837fc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
D/PMS     (  904): releaseWL(42837fc0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4227f048
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4227f048, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@4261ffe8
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
,D/PMS     (  904): acquireWL(42839de0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b65730
I/SocialFeedProvider( 1271): +onPause
,I/SocialFeedProvider( 1271): -onPause
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19434 mDataStallAlarmIntent=PendingIntent{42381e40: PendingIntentRecord{42441398 android broadcastIntent}}
W/ContextImpl( 4443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): SET_SCREEN_ON:Off
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1158): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(428404c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  904): releaseWL(42839de0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/NetworkPolicy(  904): updateScreenOn: false
,D/SmartSyncUtils( 4443): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(42847a98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4443 1000 null
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(428404c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(42847a98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4443): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
D/ContactMessageStore( 1244): Background delete complete
D/SmartSyncUtils( 4443): isEpsOn(), nState = 0
D/SmartSyncUtils( 4443): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4443): getMobilePolicyEnabled, result = true
D/WifiService(  904): New client listening to asynchronous messages
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4261ffe8
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4261ffe8, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4261ffe8, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1579): [EventService] getTotalRam: 1873 Mb
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4261ffe8
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42532640 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42532640 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1847): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1847): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1847): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1847): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1847): onScreenOff
D/AutoSetting( 1395): service - mHandler: cancel location update
D/AutoSetting( 1395): service -           changes count: 0
D/PMS     (  904): acquireWL(428605d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
D/PMS     (  904): releaseWL(428605d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - onDestroy() END
,D/AutoSetting( 1508): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4236
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  904): Killing 4236:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4236
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=3895
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3895:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3895
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{428235b8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  904): acquireWL(427d18b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): releaseWL(427d18b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(427b0a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423c7328: PendingIntentRecord{422e0930 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140996, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{41b614e0: PendingIntentRecord{425a42b8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141773, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
,D/PMS     (  904): acquireWL(427b0588): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  904): releaseWL(427b0a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  904): acquireWL(427aefd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  365): [NET] +++++ res_nsend xid =ac1d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
D/PMS     (  904): releaseWL(427aefd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1395): service - handleMessage() stop self
,D/AutoSetting( 1395): service - handleMessage() quit looper
,D/AutoSetting( 1395): service - onDestroy() END
,D/Process (  904): killProcessQuiet, pid=4262
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4262:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4262
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  904): releaseWL(427b0588): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  904): acquireWL(427aa8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=161824, Int=0
,D/PMS     (  904): releaseWL(427aa8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2252/10028)
,D/PMS     (  904): acquireWL(427aa308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(427aa308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4261c220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{423511d8: PendingIntentRecord{426ff8e8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173754, Int=0
,D/PMS     (  904): releaseWL(4261c220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(425f1058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(425f1058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(424bcb20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=221824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(424bcb20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42342910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42342910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(424000b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(424000b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(41cda868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=281824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41cda868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(41b49fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41b49fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(4241cf10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(4241cf10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42381188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=341824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42381188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(426084d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426084d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1579): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,E/PlayEventLogger( 4095): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4095): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4095): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4095): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4095): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4095): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4095): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4095): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c4d3d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 4 12 3 12
,D/libc    ( 4095): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4095): [NET] getaddrinfo-,err=8
D/libc    ( 4095): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4095): [NET] getaddrinfo-, 1
,D/libc    ( 4095): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =cfe6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4095): [NET] getaddrinfo_proxy-, success
,I/global  ( 4095): call createSocket() return a new socket.
D/libc    ( 4095): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4095): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4095): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4095): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(4267dac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4267dac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4269f1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=401825, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4269f1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425bdcc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425bdcc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(424eb4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(424eb4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(425db1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=461824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425db1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(42778190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42778190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(425331a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{41d13cf0: PendingIntentRecord{42453968 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=485826, Int=0
,D/PMS     (  904): acquireWL(4259e4e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4483 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
V/AlarmManager(  904): sending alarm PendingIntent{424eda20: PendingIntentRecord{42334948 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454970898375, Int=10800000
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(425c74f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(425331a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10047}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=6 [97][6][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/PMS     (  904): acquireWL(4266e888): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 904 1000 WorkSource{10160}
,D/PMS     (  904): releaseWL(4259e4e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(425c74f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(42556a80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(42556a80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(426199d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(426199d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4483/10047)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(42370350): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4266e888): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  904): releaseWL(42370350): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  904): killProcessQuiet, pid=3629
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3629:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3629
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(42614f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(42614f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(426677c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41d13cf0: PendingIntentRecord{42453968 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=515941, Int=0
,D/PMS     (  904): acquireWL(42591228): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): releaseWL(426677c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42669d20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(42591228): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(42669d20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(4258cb30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=521824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4258cb30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(423a2780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(423a2780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(425dfb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): releaseWL(425dfb68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4283a740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=581824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4283a740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(428251e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  904): releaseWL(428251e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4285ba30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4285ba30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1244): sku_id=99
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete,
,D/PMS     (  904): acquireWL(426aa1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=641824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426aa1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(426132f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426132f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Process (  904): killProcessQuiet, pid=3871
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3871:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.music (pid 3871): Died!
,I/ActivityManager(  904): Recipient 3871
,D/PMS     (  904): acquireWL(4265e398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(4265e398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(426610a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=701824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426610a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4281c750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4281c750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(428221c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{42671e10: PendingIntentRecord{423823d0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454971401792, Int=0
,D/PMS     (  904): releaseWL(428221c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket,
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4095): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4095): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4095): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4095): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4095): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/PMS     (  904): acquireWL(42817138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42817138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4260e878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{42336010: PendingIntentRecord{42575f28 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454971417036, Int=0
,D/PMS     (  904): releaseWL(4260e878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4095): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  904): acquireWL(42850468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=761824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42850468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4271f508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4271f508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(425fa138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(425fa138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4285f730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=821824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4285f730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4272d7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4272d7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4272f0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=881825, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4272f0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42731310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42731310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(427382d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  904): releaseWL(427382d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42622268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  904): sending alarm PendingIntent{41d89348: PendingIntentRecord{423f21e0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783656, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{41ab0b50: PendingIntentRecord{42574ea0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=927985, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{424d6270: PendingIntentRecord{424d6218 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454971618806, Int=900000
,D/PMS     (  904): acquireWL(4262d3a8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,D/PMS     (  904): releaseWL(4262d3a8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  904): Done.
D/PMS     (  904): acquireWL(426339d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): releaseWL(426339d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4443): call getInstance()
,D/PMS     (  904): releaseWL(42622268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4443): MY_DEBUG = false
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(41b9ada8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  904): acquireWL(42501ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  904): releaseWL(41b9ada8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  904): releaseWL(42501ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  904): acquireWL(426db240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=941825, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426db240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42597a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42597a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42840b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42840b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(426a1720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1001824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426a1720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(423a2cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/SmartSyncUtils( 4443): isEpsOn(), nState = 0
V/AlarmManager(  904): sending alarm PendingIntent{41f24ef8: PendingIntentRecord{4284c350 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454971689922, Int=0
D/PMS     (  904): acquireWL(422618e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4443 1000 null
,D/PMS     (  904): releaseWL(423a2cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4443): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4443): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4443): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4443): SettingOnTime = 1454979600000, randomSettingOnTime = 1454976300000
D/SmartSyncScreenOnOffTimeReceiver( 4443): SettingOffTime = 1454976000000, randomSettingOffTime = 1454976000000
D/SmartSyncScreenOnOffTimeReceiver( 4443): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4443): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4443): bNightModeTurnOffOnce = false
D/PMS     (  904): releaseWL(422618e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  904): acquireWL(42620fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): releaseWL(42620fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4271dad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4271dad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4251a260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1061824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4251a260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4256b770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/BatteryService(  904): n_update end
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
,D/PMS     (  904): releaseWL(4256b770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42633178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(42633178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4261b6a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1121825, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4261b6a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4271dfe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4271dfe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(425654a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1181825, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425654a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4258d9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+,
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4258d9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42663d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/PMS     (  904): releaseWL(42663d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(428539a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{422a2460: PendingIntentRecord{42368948 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1241824, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(428539a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42723328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/BatteryService(  904): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42723328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42844970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(42844970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1579): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1579): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4531): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4531): ====startRecUseTime====
D/htc.customization.log.level( 4531):  is 
W/CustomizationLogLevel( 4531): Level value is invalid, use default level 2
D/CustomizationManager( 4531):  Read ACC file spent 0.121 (s)
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4531): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4531): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4531): Parsing tag category name = system
I/CustomizationCIDLoader( 4531): Parsing tag category name = application
I/CustomizationCIDLoader( 4531): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4531): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4531): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4531): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4531): Parsing tag category name = Settings
D/CustomizationManager( 4531):  Read CID file spent 0.176 (s)
D/CustomizationManager( 4531):  All configurations done spent 0.177 (s)
W/HtcNativeFlag( 4531): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4531): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4531): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4531): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4531, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  904): Skipping PackageSetting{42218718 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
D/DotMatrix( 1579): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1579): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1579): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/acms    ( 1902): Unregistering com.test.thalitest
E/acms    ( 1902): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(426857e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
W/PackageManager(  904): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  904): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/PMS     (  904): releaseWL(426857e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PackageBroadcastService( 2252): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4545 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/ActivityManager(  904): Delaying start of: ServiceRecord{425a1e70 u0 com.google.android.gms/.wearable.service.WearableControlService}
E/ExternalAccountType( 1326): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2252): CP2 sync disabled
I/MultiDex( 4545): install
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2252, uid=10028, userID:0
I/MultiDex( 4545): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4545): loading existing secondary dex files
I/MultiDex( 4545): load found 1 secondary dex files
D/PMS     (  904): acquireWL(4262f998): PARTIAL_WAKE_LOCK  Icing 0x1 2252 10028 null
I/Icing   ( 2252): doRemovePackageData com.test.thalitest
I/MultiDex( 4545): install done
D/PMS     (  904): releaseWL(4262f998): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4565 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4545): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
E/SQLiteDatabase( 2252): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2252): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2252): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2252): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2252): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2252): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2252): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2252): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2252): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2252): Runtime exception while performing operation
E/ClearPendingStateOp( 2252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2252): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2252): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2252): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2252): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2252): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2252): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2252): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2252): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2252): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2252): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2252): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2252): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2252): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2252): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2252): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2252): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2252): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4565): install
I/MultiDex( 4565): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4565): loading existing secondary dex files
I/MultiDex( 4565): load found 1 secondary dex files
E/DropBoxManagerService(  904): Can't write: system_app_wtf
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/MultiDex( 4565): install done
I/ProviderInstaller( 4565): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Resuming delayed broadcast
E/SharedPreferencesImpl( 1210): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1395): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1395): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1395): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c98bac0
W/[PluginManager]RegisterService( 1395): provider may killed!
W/[PluginManager]RegisterService( 1395): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1395): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1395): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1395): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1395): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1395): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1395): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1395): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1395): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1395): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1395): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1395): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1395): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1395): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1395): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 4545): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4545): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4545): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4545): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4545): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4545): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4545): threadid=12: thread exiting with uncaught exception (group=0x41686e30)
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2892): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/AndroidRuntime( 4545): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4545): Process: com.google.android.gms.drive, PID: 4545
E/AndroidRuntime( 4545): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4545): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4545): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4545): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4545): 	at ctn.run(SourceFile:985)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
D/Process ( 4545): killProcess, pid=4545
D/Process ( 4545): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Recipient 4545
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4545) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4587 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2892): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2892): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63619df8
W/dalvikvm( 2892): threadid=14: thread exiting with uncaught exception (group=0x41686e30)
E/AndroidRuntime( 2892): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2892): Process: com.google.android.googlequicksearchbox:search, PID: 2892
E/AndroidRuntime( 2892): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2892): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2892): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2892): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2892): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2892): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2892): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2892): 	at cid.d(PG:186)
E/AndroidRuntime( 2892): 	at clo.g(PG:594)
E/AndroidRuntime( 2892): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2892): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2892): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2892): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2892): 	at clr.tL(PG:827)
E/AndroidRuntime( 2892): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2892): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2892): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2892): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2892): killProcess, pid=2892
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
D/Process ( 2892): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  904): Recipient 2892
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2892) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/WifiService(  904): Client connection lost with reason: 4
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2892): Died!
E/SQLiteDatabase( 2252): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2252): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2252): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2252): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2252): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2252): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2252): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2252): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2252): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2252): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2252): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2252): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2252): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2252): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2252): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2252): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2252): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2252): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2252): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2252): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2252): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2252): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2252): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2252): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2252): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2252): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2252): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2252): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 2252): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 2252): threadid=10: thread exiting with uncaught exception (group=0x41686e30)
E/AndroidRuntime( 2252): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2252): Process: com.google.android.gms, PID: 2252
E/AndroidRuntime( 2252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2252): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2252): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2252): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2252): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2252): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2252): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2252): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2252): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2252): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2252): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms
D/Process (  904): killProcessQuiet, pid=2252
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
W/ActivityManager(  904): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  904): Killing 2252:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b49d70 +
I/Prism.WidgetManager( 1271): onLoadItems() +
E/SQLiteDatabase( 4587): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4587): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4587): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4587): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4587): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4587): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4587): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4587): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4587): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4587): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4587): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4587): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4587): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4587): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4587): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4587): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4587): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4587): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4587): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4587): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4587): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4587): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4587): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4587): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4587): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4587): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4587): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4587): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4587): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4587): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4587): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4587): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4587): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4587): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4587): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4587): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4587): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4587): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4587): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4587): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4587): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4587): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4587): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4587): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4587): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4587): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4587): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4587): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4587): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4587): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4587): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4587): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4587): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4587): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4587): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4587): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4587): threadid=11: thread exiting with uncaught exception (group=0x41686e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4587): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4587): Process: com.google.android.apps.docs, PID: 4587
E/AndroidRuntime( 4587): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4587): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4587): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4587): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4587): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4587): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4587): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4587): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4587): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
D/Process ( 4587): killProcess, pid=4587
D/Process ( 4587): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4605 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4587
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4587) has died.

```
