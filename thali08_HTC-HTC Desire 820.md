#### Test 587523534d3a10e_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1488): handler message = 4011
E/HtcModeClient( 1488): Check connection and retry 8 times.
,D/CustomizationManager( 4242): ====startRecUseTime====
D/htc.customization.log.level( 4242):  is 
W/CustomizationLogLevel( 4242): Level value is invalid, use default level 2
D/CustomizationManager( 4242):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4242): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4242): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4242): Parsing tag category name = system
I/CustomizationCIDLoader( 4242): Parsing tag category name = application
I/CustomizationCIDLoader( 4242): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4242): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4242): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4242): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4242): Parsing tag category name = Settings
D/CustomizationManager( 4242):  Read CID file spent 0.119 (s)
D/CustomizationManager( 4242):  All configurations done spent 0.119 (s)
W/HtcNativeFlag( 4242): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4242): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4242): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4242): Fail to get flag for type 'language', use default value: -1
E/cutils-trace( 4242): Error opening trace file: No such file or directory (2)
--------- beginning of /dev/log/system
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4242
,V/AlarmManager(  907): sending alarm PendingIntent{426debe0: PendingIntentRecord{4245ddf0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=71182, Int=0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): acquireWL(426f2dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=99
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(426f2dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:99 unsupport:false plugged:true
,I/CalendarProvider2( 1488): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1488): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(426bbec8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3885 10154 null
,I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3885): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3885): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3885, uid=10154, userID:0
,I/MusicLeanback( 3885): Conditions not met for autocaching.
,I/MusicLeanback( 3885): Stop autocaching.
D/PMS     (  907): releaseWL(426bbec8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4259 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4259): Loading default preferences
,W/Resources( 4259): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 4259): Overriding preferences with custom values
,D/SyncApplication( 4259): Updating preferences succeeded
E/SyncApplication( 4259): Application created.
D/VolumeInfo( 4259): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 4259): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4259): Found 0 mount point(s)
V/VolumeInfo( 4259): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 4259): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/CalendarDefines( 4259): getNewCalendarAuthority()...
D/SyncApplication( 4259): enableAppOperation()+
D/VolumeInfo( 4259): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 4259): Can not create volume ID for unmounted volume null
D/SyncApplication( 4259): enableAppOperation()-
D/HTCUtilities( 4259): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4259, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4259, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4259): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4259): isNeorSinged() return false
,D/CDMountReceiver( 4259): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4259): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4259): enable CD Auto-mount: true
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4259): enable auto-mount
,D/HTCUtilities( 4259): enable auto-mount
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
I/ActivityManager(  907): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  907): Resuming delayed broadcast
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c5b910 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 13 3 11
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c5c090 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 2 9 3 16
,W/MediaManager( 3844): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  907): killProcessQuiet, pid=3411
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3411:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.uploader.UploaderAlarmReceiver
,W/Uploader( 2249): No account for auth token provided
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{426acbd0 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4283 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=44 rxSum=34} preTxRxSum={txSum=22 rxSum=17}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20037 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20038 delay=15s
D/PMS     (  907): releaseWL(42664bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    ( 2249): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2249): [NET] getaddrinfo-,err=8
D/libc    ( 2249): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2249): [NET] getaddrinfo-, 1
,D/libc    ( 2249): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =29cb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/CalendarApplication( 4283): onCreate
D/ProviderChangeReceiver( 4283): ---------------------------------------------------
,D/ProviderChangeReceiver( 4283): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4283): start to updateAlertNotification!
I/ActivityManager(  907): Recipient 3411
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 297
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2249): [NET] getaddrinfo_proxy-, success
,I/global  ( 2249): call createSocket() return a new socket.
D/libc    ( 2249): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2249): [NET] getaddrinfo-, SUCCESS
,I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4300 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3725
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3725:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3725
,D/AlertService( 4283): No fired or scheduled alerts
,D/HtcAlertUtils( 4283): -- cancelReminderNotification --
,D/HtcAlertUtils( 4283): broadcastExistReminder!
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 2249): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2249): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2249/10028)
W/Uploader( 2249): No account for auth token provided
,V/Settings:HtcSettingsApplication( 4300): [4300/4300] onCreate()
W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2249/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2249/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2249/10028)
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3904
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3904:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3904
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=7 [13][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 9 times.
,I/SensorManager(  907): mEventCount = 750
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): releaseWL(41ec2380): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:84, mTXpacketCount:70, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 10 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): acquireWL(4236a1b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10073}
,V/AlarmManager(  907): sending alarm PendingIntent{425b2380: PendingIntentRecord{425a64e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455029383893, Int=0
,D/PMS     (  907): releaseWL(4236a1b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4132): [1] 5.onFinished: Installation state replication succeeded.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/SensorManager(  907): mEventCount = 900
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1402): service - mHandler: update timezone
,D/AutoSetting( 1402): service - handleMessage() stop self
,D/AutoSetting( 1402): service - handleMessage() quit looper
,D/AutoSetting( 1402): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=3940
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3940:com.htc.sdm/u0a80 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3940
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1488): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1488): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1488): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1488): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1488): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1488): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1488): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1488): service - mHandler: update timezone
,D/AutoSetting( 1488): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1488): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1488): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1488): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c5e068 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 4 8 3 11
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 11 times.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=57 rxSum=43} preTxRxSum={txSum=44 rxSum=34}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20038 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20039 delay=15s
D/PMS     (  907): acquireWL(423dbea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42625090: PendingIntentRecord{4245ddf0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88527, Int=0
D/PMS     (  907): releaseWL(423dbea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 12 times.
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  907): mEventCount = 1050
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:87, mTXpacketCount:84, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1488): Don't start project servcice
,D/HtcModeClient( 1488): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1488): connectState: CONNECTION_READY = false
,D/SilentMusic( 1488): call stop
,D/HtcModeClient( 1488): close connection
,W/HtcModeClient( 1488): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1488): read the terminate packet, so break
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): acquireWL(424dc668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=97043, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(424dc668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1117): now=1455029400058 next=59942
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425a21e0 u0 com.htc.htclocationservice/.AutoSettingService}
,I/SensorManager(  907): mEventCount = 1200
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(42455bd0): PARTIAL_WAKE_LOCK  Icing 0x1 2249 10028 null
,D/PMS     (  907): releaseWL(42455bd0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42633728): PARTIAL_WAKE_LOCK  Icing 0x1 2249 10028 null
,D/PMS     (  907): releaseWL(42633728): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425fc158): PARTIAL_WAKE_LOCK  Icing 0x1 2249 10028 null
,D/PMS     (  907): releaseWL(425fc158): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4255c470): PARTIAL_WAKE_LOCK  Icing 0x1 2249 10028 null
,D/PMS     (  907): releaseWL(4255c470): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=58 rxSum=44} preTxRxSum={txSum=57 rxSum=43}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20039 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20040 delay=15s
D/PMS     (  907): acquireWL(425aa5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{425aaf08: PendingIntentRecord{4245ddf0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103534, Int=0
D/PMS     (  907): releaseWL(425aa5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97,
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4325 uid=10077 gids={50077}
,D/PMS     (  907): acquireWL(42660880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
,V/AlarmManager(  907): sending alarm PendingIntent{424831f0: PendingIntentRecord{42108190 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455029407610, Int=60000
,D/PMS     (  907): releaseWL(42660880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/SMSBackup( 4325): SMSBackupAgentService started
,D/SMSBackup( 4325): Checking restore status
,D/SMSBackup( 4325): Restore complete
,D/SMSBackup( 4325): cancelCheckAlarm
,D/SMSBackup( 4325): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  907): killProcessQuiet, pid=3975
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Killing 3975:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Recipient 3975
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:87, mTXpacketCount:87, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SensorManager(  907): mEventCount = 1350
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421be7e0
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  907): setLight #0: color=#0
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421be7e0, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42014bf8
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@41f860a8
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 413ms
,W/PnPMgr  (  357): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): OOBE c monitor 11
,I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/NfcService( 1257): ScreenObserver: OFF
,D/NfcService( 1257): applyRouting - 0
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1257): applyRouting -2
I/InputMethodManagerService(  907): Disable input method client, pid=1272
D/PMS     (  907): acquireWL(427eca80): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  907): releaseWL(427eca80): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  907): acquireWL(427edae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(427edae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425fd8b0)
D/PMN     (  907): wakingUp
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/HtcPowerSaver(  907): updateBatteryInfo
I/WindowManager(  907): No lock screen! windowToken=null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMN     (  907): onScreenOn
D/PowerUI ( 1117): closing low battery warning: level=99
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,D/MtpService( 2446): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20041 delay=15s
D/MtpService( 2446): [MTP][onReceive]-
,D/NfcService( 1257): applyRouting - 0
,D/NfcService( 1257): applyRouting -2
I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PMS     (  907): acquireWL(426a5d60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  907): releaseWL(426a5d60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ClockThread( 1117): stop update clock
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
V/NotificationService(  907): batLight: plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c80000
D/qdlights(  907): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4346 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WIFI_ICON( 1117): WifiActivity: 0
V/NotificationService(  907): batLight: plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c80000
D/qdlights(  907): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
,D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:99 unsupport:false plugged:true
,D/NetworkPolicy(  907): updateScreenOn: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1797): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1797): onScreenOn: 1455029414424
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1797): onScreenOn: 1455029414424
D/PMS     (  907): acquireWL(426a3578): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1466 10028 null
D/PMS     (  907): releaseWL(426a3578): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42014bf8
D/PMS     (  907): acquireWL(42595f38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4346 1000 null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42014bf8, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@41f860a8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
,D/PMS     (  907): acquireWL(425973e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b297c0
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/SmartSyncUtils( 4346): isEpsOn(), nState = 0
,D/PMS     (  907): releaseWL(42595f38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20041 mDataStallAlarmIntent=PendingIntent{42629f28: PendingIntentRecord{4245ddf0 android broadcastIntent}}
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
D/PMS     (  907): releaseWL(425973e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:Off
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
,D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(42591b60): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/NetworkPolicy(  907): updateScreenOn: false
,D/SmartSyncUtils( 4346): getMobilePolicyEnabled, result = true
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/AutoSetting( 1402): receiver - intent: android.intent.action.USER_PRESENT
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42591b60): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/AutoSetting( 1402): service - onCreate()
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1402): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  907): request 424c7dd0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/TetherSettings( 4190): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4190): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4190): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4190): Cust_ConnectToPC   : spcsc>false
D/        ( 4190): Cust_ConnectToPC   : IPT>true
,D/        ( 4190): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4190): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4190): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4190): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4190): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4190): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4190):  defaultType:0
D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
D/ContactMessageStore( 1243): Background delete complete
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1797): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1797): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1797): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1797): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1797): onScreenOff
,D/SmartSyncUtils( 4346): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4346): getMobilePolicyEnabled, result = true
W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): acquireWL(425a05b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1466 10028 null
D/PMS     (  907): releaseWL(425a05b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/SmartSyncUtils( 4346): isEpsOn(), nState = 0
D/WifiService(  907): New client listening to asynchronous messages
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41f860a8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41f860a8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41f860a8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41f860a8
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424a9d80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424a9d80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1488): service - handleMessage() stop self
,D/AutoSetting( 1488): service - onDestroy() END
,D/AutoSetting( 1488): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4001
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4001:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4001
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=3919
,I/ActivityManager(  907): Killing 3919:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3919
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1402): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1402): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{424e3058 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  907): acquireWL(4273ebc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=99
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4273ebc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,D/PMS     (  907): acquireWL(42779b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42779b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/BatteryController( 1117): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4277c338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{425023b0: PendingIntentRecord{424e7318 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141615, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42626ef0: PendingIntentRecord{425f8a98 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141642, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{423e8858: PendingIntentRecord{42673e40 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455029438967, Int=1800000
,D/AutoSetting( 1402): service - handleMessage() stop self
,D/AutoSetting( 1402): service - handleMessage() quit looper
,D/AutoSetting( 1402): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4036
,I/ActivityManager(  907): Killing 4036:com.htc.task.gtask/u0a67 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4036
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
,D/PMS     (  907): acquireWL(42781f20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1364/10028)
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3043 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  907): acquireWL(42791350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  907): acquireWL(42791ad8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2249 10028 null
,D/PMS     (  907): releaseWL(4277c338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  907): releaseWL(42791350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  907): acquireWL(42793848): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2249 10028 null
,I/EventLogService( 2249): Aggregate from 1455029357077 (log), 1455027638928 (data)
D/PMS     (  907): releaseWL(42791ad8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  907): releaseWL(42793848): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): releaseWL(42781f20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(427bc020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427bc020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(427be9a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{42588a90: PendingIntentRecord{426437b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174406, Int=0
,D/PMS     (  907): releaseWL(427be9a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2249/10028)
,D/PMS     (  907): acquireWL(427c23a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427c23a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(427c3070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1595): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/DotMatrix( 1569): [EventService] reorderNotification, total:0
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(427c3070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/TetherSettings( 4190): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4190): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4190): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4190): Cust_ConnectToPC   : spcsc>false
D/        ( 4190): Cust_ConnectToPC   : IPT>true
D/        ( 4190): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4190): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4190): Index of the first 1 = -1
,W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4190): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4190): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4190): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4190): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(427cdc50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  907): releaseWL(427cdc50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(427cfeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427cfeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(427d17b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=277044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427d17b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(427d3a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427d3a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(427d4700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(427d4700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(427dbb08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=337044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427dbb08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cd33b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4132): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4132): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4132): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4132): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4132): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 10 3 12
,D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4132): [NET] getaddrinfo-,err=8
D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4132): [NET] getaddrinfo-, 1
,D/libc    ( 4132): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5ffb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4132): [NET] getaddrinfo_proxy-, success
I/global  ( 4132): call createSocket() return a new socket.
D/libc    ( 4132): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4132): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4132): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(42835040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42835040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42836940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42836940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(42838c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42838c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4283a588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=457044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4283a588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4283c7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4283c7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4283e0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=517044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4283e0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(42840368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42840368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42841c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=577044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42841c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42843ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42843ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  907): acquireWL(428457c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=637044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428457c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=3740
,I/ActivityManager(  907): Killing 3740:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3740
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4284abc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4284abc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4284c4c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=697044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4284c4c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4284ece8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4284ece8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(428505e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=757044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428505e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42852890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42852890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42853560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42853560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4285a908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=817044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4285a908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4285cba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4285cba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42863f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=877044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42863f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42866210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42866210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4286d5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=937044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4286d5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4286fe20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4286fe20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42871720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42871720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(428749d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41e21e80: PendingIntentRecord{42454430 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784322, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{41fa9c30: PendingIntentRecord{424498e0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928565, Int=0
,D/PMS     (  907): acquireWL(42882838): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): releaseWL(42882838): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4393 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42584218: PendingIntentRecord{42576230 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455029524008, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{426626f8: PendingIntentRecord{42658188 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455030244334, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{426283d0: PendingIntentRecord{42667368 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455030314602, Int=0
,W/ContextImpl( 4346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(42889730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PowerUsageService( 4346): call getInstance()
,D/SmartSyncUtils( 4346): isEpsOn(), nState = 0
,D/PMS     (  907): releaseWL(42889730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageList:PowerUsageHelper( 4346): MY_DEBUG = false
D/PMS     (  907): acquireWL(4288b778): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4346 1000 null
,D/PMS     (  907): releaseWL(428749d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4346): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4346): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4346): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4346): SettingOnTime = 1455084000000, randomSettingOnTime = 1455080994000
D/SmartSyncScreenOnOffTimeReceiver( 4346): SettingOffTime = 1455062400000, randomSettingOffTime = 1455063998000
D/SmartSyncScreenOnOffTimeReceiver( 4346): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4346): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4346): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(4288b778): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4393/10047)
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Process (  907): killProcessQuiet, pid=4085
,I/ActivityManager(  907): Killing 4085:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4085
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42858280): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  907): releaseWL(42858280): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  907): acquireWL(427c7df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  907): releaseWL(427c7df8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  907): acquireWL(427d86b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427d86b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(427d9228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(427d9228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(426a5998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426a5998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425fb908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(425fb908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(425dec18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1117044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425dec18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42692628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/BatteryService(  907): n_update end
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42692628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42718808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42718808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4288d280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1177044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4288d280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4288f520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4288f520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  907): Checking...
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  907): acquireWL(426f6f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426f6f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(426f8878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421037e0: PendingIntentRecord{423713b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1237044, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426f8878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(427b0198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427b0198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4416): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4416): ====startRecUseTime====
D/htc.customization.log.level( 4416):  is 
W/CustomizationLogLevel( 4416): Level value is invalid, use default level 2
D/CustomizationManager( 4416):  Read ACC file spent 0.123 (s)
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4416): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4416): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4416): Parsing tag category name = system
I/CustomizationCIDLoader( 4416): Parsing tag category name = application
I/CustomizationCIDLoader( 4416): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4416): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4416): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4416): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4416): Parsing tag category name = Settings
D/CustomizationManager( 4416):  Read CID file spent 0.180 (s)
D/CustomizationManager( 4416):  All configurations done spent 0.180 (s)
W/HtcNativeFlag( 4416): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4416): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4416): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4416): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4416, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  907): Skipping PackageSetting{42264b98 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
W/PackageManager(  907): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  907): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1897): Unregistering com.test.thalitest
E/acms    ( 1897): Could not unregister removed application com.test.thalitest
D/PMS     (  907): acquireWL(42891a20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1466 10028 null
W/GeofencerStateMachine( 1466): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): releaseWL(42891a20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Scheme: "mms"
D/PackageBroadcastService( 2249): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4430 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/ActivityManager(  907): Delaying start of: ServiceRecord{42711228 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4430): install
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2249): CP2 sync disabled
I/MultiDex( 4430): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4430): loading existing secondary dex files
I/MultiDex( 4430): load found 1 secondary dex files
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2249, uid=10028, userID:0
I/MultiDex( 4430): install done
I/Icing   ( 2249): doRemovePackageData com.test.thalitest
E/Icing   ( 2249): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 2249): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 2249): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
D/PMS     (  907): acquireWL(425fd990): PARTIAL_WAKE_LOCK  Icing 0x1 2249 10028 null
E/Icing   ( 2249): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 2249): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 2249): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 2249): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 2249): Writing status failed
D/PMS     (  907): releaseWL(425fd990): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4450 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4430): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4450): install
I/MultiDex( 4450): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/SQLiteDatabase( 2249): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2249): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2249): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2249): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2249): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2249): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2249): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2249): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2249): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4450): loading existing secondary dex files
E/ClearPendingStateOp( 2249): Runtime exception while performing operation
E/ClearPendingStateOp( 2249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2249): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2249): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2249): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2249): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2249): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2249): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2249): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2249): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4450): load found 1 secondary dex files
F/ClearPendingStateOp( 2249): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2249): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2249): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2249): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2249): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2249): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2249): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2249): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2249): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4450): install done
I/ProviderInstaller( 4450): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/DropBoxManagerService(  907): Can't write: system_app_wtf
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/ActivityManager(  907): Resuming delayed broadcast
E/SharedPreferencesImpl( 1209): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1402): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SQLiteLog( 1402): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1402): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c8ff1b8
W/[PluginManager]RegisterService( 1402): provider may killed!
W/[PluginManager]RegisterService( 1402): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1402): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1402): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1402): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
E/SQLiteDatabase( 4430): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4430): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4430): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4430): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4430): threadid=12: thread exiting with uncaught exception (group=0x416e5e30)
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
E/AndroidRuntime( 4430): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4430): Process: com.google.android.gms.drive, PID: 4430
E/AndroidRuntime( 4430): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4430): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4430): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4430): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4430): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4430): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4430): 	at ctn.run(SourceFile:985)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
D/Process ( 4430): killProcess, pid=4430
D/Process ( 4430): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2898): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Recipient 4430
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4430) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4471 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2898): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2898): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5d8d74c8
W/dalvikvm( 2898): threadid=14: thread exiting with uncaught exception (group=0x416e5e30)
E/AndroidRuntime( 2898): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2898): Process: com.google.android.googlequicksearchbox:search, PID: 2898
E/AndroidRuntime( 2898): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2898): 	at cid.d(PG:186)
E/AndroidRuntime( 2898): 	at clo.g(PG:594)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2898): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2898): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2898): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2898): 	at clr.tL(PG:827)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2898): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2898): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2898): killProcess, pid=2898
D/Process ( 2898): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
W/SQLiteConnectionPool( 2249): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 2249): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 2249): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/PackageManager(  907): Unable to load service info ResolveInfo{425447e0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  907): Recipient 2898
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 2898) has died.
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2898): Died!
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
E/SQLiteDatabase( 2249): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2249): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2249): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2249): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2249): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2249): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2249): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2249): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2249): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2249): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2249): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2249): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2249): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2249): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2249): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2249): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2249): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2249): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2249): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2249): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2249): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2249): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2249): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2249): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2249): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2249): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2249): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2249): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2249): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2249): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2249): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2249): 	at java.lang.Thread.run(Thread.java:864)
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10998ms
W/SQLiteOpenHelper( 2249): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 2249): threadid=10: thread exiting with uncaught exception (group=0x416e5e30)
E/AndroidRuntime( 2249): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2249): Process: com.google.android.gms, PID: 2249
E/AndroidRuntime( 2249): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2249): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2249): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2249): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2249): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2249): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2249): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2249): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2249): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2249): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2249): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2249): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2249): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2249): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2249): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
D/Process (  907): killProcessQuiet, pid=2249
W/ActivityManager(  907): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  907): Killing 2249:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4471): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4471): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4471): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4471): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4471): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4471): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4471): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4471): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4471): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4471): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4471): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4471): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4471): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4471): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4471): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4471): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4471): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4471): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4471): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4471): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4471): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4471): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4471): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4471): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4471): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4471): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4471): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4471): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4471): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4471): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4471): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4471): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4471): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4471): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4471): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4471): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4471): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4471): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4471): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4471): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4471): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4471): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4471): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4471): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4471): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4471): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4471): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4471): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4471): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4471): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4471): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4471): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4471): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4471): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4471): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4471): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4471): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4471): threadid=11: thread exiting with uncaught exception (group=0x416e5e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4471): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4471): Process: com.google.android.apps.docs, PID: 4471
E/AndroidRuntime( 4471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4471): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4471): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4471): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4471): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4471): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
E/SQLiteDatabase( 4471): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4471): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4471): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4471): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4471): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4471): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4471): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4471): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4471): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4471): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4471): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4471): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4471): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4471): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4471): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4471): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4471): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4471): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4471): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4471): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4471): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4471): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4471): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4471): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4471): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4471): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4471): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4471): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4471): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4471): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4471): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4471): Opened ClientFlag.db in read-only mode
D/Process ( 4471): killProcess, pid=4471
D/Process ( 4471): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4490 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4471
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  907): killProcessQuiet, pid=4168
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4168:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4471) has died.
I/ActivityManager(  907): Recipient 4168
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4490): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687, 
E/SQLiteDatabase( 4490): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4490): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4490): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4490): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4490): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4490): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4490): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4490): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4490): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4490): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4490): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
