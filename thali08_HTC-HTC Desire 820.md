#### Test 581356550b07fff_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
--------- beginning of /dev/log/main
D/TodoTaskshortcut( 3934): update TASK shortcut>
D/Process (  906): killProcessQuiet, pid=3800
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3800:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
I/ActivityManager(  906): Recipient 3800
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/CustomizationManager( 4217): ====startRecUseTime====
D/htc.customization.log.level( 4217):  is 
W/CustomizationLogLevel( 4217): Level value is invalid, use default level 2
D/CustomizationManager( 4217):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4217): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4217): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4217): Parsing tag category name = system
I/CustomizationCIDLoader( 4217): Parsing tag category name = application
I/CustomizationCIDLoader( 4217): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4217): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4217): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4217): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4217): Parsing tag category name = Settings
D/CustomizationManager( 4217):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4217):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4217): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4217): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4217): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4217): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4217
E/cutils-trace( 4217): Error opening trace file: No such file or directory (2)
I/HtcModeClient( 1534): handler message = 4011
E/HtcModeClient( 1534): Check connection and retry 8 times.
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/HABCtrl (  906): TPE algorithm. remove timeout.
,D/HABCtrl (  906): ALG=2, lsvalue=10(0th)->40(1th), last_level=-1, lValue=39->64
,V/AlarmManager(  906): sending alarm PendingIntent{425c13a0: PendingIntentRecord{425a0518 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=71363, Int=0
,D/PMS     (  906): acquireWL(4273d578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4273d578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/CalendarProvider2( 1534): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1534): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42720f90): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3860 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3860): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3860): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3860, uid=10154, userID:0
,I/MusicLeanback( 3860): Conditions not met for autocaching.
,I/MusicLeanback( 3860): Stop autocaching.
D/PMS     (  906): releaseWL(42720f90): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4235 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4235): Loading default preferences
,W/Resources( 4235): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 4235): Overriding preferences with custom values
,D/SyncApplication( 4235): Updating preferences succeeded
,E/SyncApplication( 4235): Application created.
D/VolumeInfo( 4235): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4235): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4235): Found 0 mount point(s)
,V/VolumeInfo( 4235): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4235): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4235): getNewCalendarAuthority()...
,D/VolumeInfo( 4235): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4235, uid=10008, userID:0
,W/VolumeInfo( 4235): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4235): enableAppOperation()+
,D/SyncApplication( 4235): enableAppOperation()-
,D/HTCUtilities( 4235): isNeorSinged() + 
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4235, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4235): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4235): isNeorSinged() return false
,D/CDMountReceiver( 4235): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4235): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4235): enable CD Auto-mount: true
,D/HTCUtilities( 4235): enable auto-mount
,D/HTCUtilities( 4235): enable auto-mount
I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1116): com.nero.android.htc.sync (false,0)
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41bde648 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.nero.android.htc.sync 2 12 3 11
,I/RemoteViews( 1116): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41be5f18 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 3820): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  906): killProcessQuiet, pid=3389
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3389:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.uploader.UploaderAlarmReceiver
,W/Uploader( 1223): No account for auth token provided
I/ActivityManager(  906): Recipient 3389
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e932 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 293
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
I/global  ( 1223): call createSocket() return a new socket.
D/libc    ( 1223): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-, SUCCESS
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,W/Uploader( 1223): No account for auth token provided
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4260 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=65 rxSum=49} preTxRxSum={txSum=47 rxSum=33}
,D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19558 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19559 delay=15s
D/PMS     (  906): releaseWL(426d4db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/CalendarApplication( 4260): onCreate
D/ProviderChangeReceiver( 4260): ---------------------------------------------------
,D/ProviderChangeReceiver( 4260): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4260): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4275 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=3708
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3708:com.htc.sense.news/u0a75 (adj 15): empty #17
,D/AlertService( 4260): No fired or scheduled alerts
,D/HtcAlertUtils( 4260): -- cancelReminderNotification --
,D/HtcAlertUtils( 4260): broadcastExistReminder!
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3708
,V/Settings:HtcSettingsApplication( 4275): [4275/4275] onCreate()
W/ContextImpl( 4275): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4269d1c8 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3947
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3947:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3947
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [13][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 91
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 750
,I/HtcModeClient( 1534): handler message = 4011
,E/HtcModeClient( 1534): Check connection and retry 9 times.
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): releaseWL(42404e10): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 110
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:95, mTXpacketCount:82, avgLinkspeed:22,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1534): handler message = 4011
,E/HtcModeClient( 1534): Check connection and retry 10 times.
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): acquireWL(423bc9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{425fedc8: PendingIntentRecord{4242a0d8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454950359287, Int=0
,D/PMS     (  906): releaseWL(423bc9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4109): [1] 5.onFinished: Installation state replication succeeded.
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  906): mEventCount = 900
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1399): service - mHandler: update timezone
,D/AutoSetting( 1399): service - handleMessage() stop self
,D/AutoSetting( 1399): service - handleMessage() quit looper
,D/AutoSetting( 1399): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=3881
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3881:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3881
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1534): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1534): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1534): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1534): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1534): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1534): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1534): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1534): service - mHandler: update timezone
,D/AutoSetting( 1534): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1534): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1534): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1534): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c8d178 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 1 7 2 11
,I/HtcModeClient( 1534): handler message = 4011
,E/HtcModeClient( 1534): Check connection and retry 11 times.
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=67 rxSum=51} preTxRxSum={txSum=65 rxSum=49}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19559 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19560 delay=15s
D/PMS     (  906): acquireWL(42548cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41cc45c8: PendingIntentRecord{425a0518 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88175, Int=0
D/PMS     (  906): releaseWL(42548cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 83
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 1534): handler message = 4011
,E/HtcModeClient( 1534): Check connection and retry 12 times.
,I/SensorManager(  906): mEventCount = 1050
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=50 [2][1][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 109
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:101, mTXpacketCount:95, avgLinkspeed:21,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1534): handler message = 4011
,E/HtcModeClient( 1534): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1534): Don't start project servcice
,D/HtcModeClient( 1534): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1534): connectState: CONNECTION_READY = false
D/SilentMusic( 1534): call stop
D/HtcModeClient( 1534): close connection
,W/HtcModeClient( 1534): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1534): read the terminate packet, so break
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  906): mEventCount = 1200
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{423ae620 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): acquireWL(425a3fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=101340, Int=0
,D/PMS     (  906): releaseWL(425a3fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1116): now=1454950380050 next=59950
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): acquireWL(4266eb50): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(4266eb50): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42729fe0): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(42729fe0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4276a160): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(4276a160): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(426f5648): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(426f5648): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=69 rxSum=53} preTxRxSum={txSum=67 rxSum=51}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19560 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19561 delay=15s
D/PMS     (  906): acquireWL(425c4390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{423cf5f8: PendingIntentRecord{425a0518 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103179, Int=0
D/PMS     (  906): releaseWL(425c4390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4299 uid=10077 gids={50077}
D/PMS     (  906): acquireWL(425c2288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
V/AlarmManager(  906): sending alarm PendingIntent{425d0d10: PendingIntentRecord{42661f50 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454950382486, Int=60000
,D/PMS     (  906): releaseWL(425c2288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4299): SMSBackupAgentService started
,D/SMSBackup( 4299): Checking restore status
,D/SMSBackup( 4299): Restore complete
,D/SMSBackup( 4299): cancelCheckAlarm
,D/SMSBackup( 4299): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3987
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3987:com.htc.task.gtask/u0a67 (adj 15): empty #17
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Recipient 3987
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  906): mEventCount = 1350
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 95
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:101, mTXpacketCount:101, avgLinkspeed:19,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421da670
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  906): setLight #0: color=#0
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421da670, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420de888
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4214a1a0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 417ms
,W/PnPMgr  (  357): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,D/NfcService( 1253): ScreenObserver: OFF
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42682740)
I/InputMethodManagerService(  906): Disable input method client, pid=1271
,D/PMN     (  906): wakingUp
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMS     (  906): acquireWL(42767b20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): acquireWL(427687f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  906): releaseWL(42767b20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19562 delay=15s
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
D/PMS     (  906): releaseWL(427687f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMN     (  906): onScreenOn
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2427): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/MtpService( 2427): [MTP][onReceive]-
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/NfcService( 1253): applyRouting - 0
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/NfcService( 1253): applyRouting -2
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PMS     (  906): acquireWL(426ef670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  906): releaseWL(426ef670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:On
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1161): BG scan when screen On
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): Match BG scan, scan!
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1116): stop update clock
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4318 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WIFI_ICON( 1116): WifiActivity: 0
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,D/NetworkPolicy(  906): updateScreenOn: false
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1805): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): onScreenOn: 1454950389736
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1805): onScreenOn: 1454950389736
D/PMS     (  906): acquireWL(42646850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
D/PMS     (  906): releaseWL(42646850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  906): acquireWL(42647bf0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4318 1000 null
D/SmartSyncUtils( 4318): isEpsOn(), nState = 0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420de888
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420de888, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4214a1a0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
,I/FeedHostManager( 1271): [onPause]
,I/FeedProviderManager( 1271): onPause
,D/PMS     (  906): acquireWL(42688230): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c747f0
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19562 mDataStallAlarmIntent=PendingIntent{41ee8cf8: PendingIntentRecord{425a0518 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42647bf0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  906): acquireWL(42777890): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(42688230): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/SmartSyncUtils( 4318): getMobilePolicyEnabled, result = true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:Off
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1161): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
,D/Process (  906): killProcessQuiet, pid=3915
D/PMS     (  906): releaseWL(42777890): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/ActivityManager(  906): Killing 3915:com.htc.sdm/u0a80 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1399): receiver - intent: android.intent.action.USER_PRESENT
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3915
,D/AutoSetting( 1399): service - onCreate()
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/AutoSetting( 1399): service - AddressCache: using context: com.htc.Weather
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4167): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4167): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4167): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4167): Cust_ConnectToPC   : spcsc>false
D/        ( 4167): Cust_ConnectToPC   : IPT>true
,D/        ( 4167): Cust_ConnectToPC   : Singel_USB>false
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/NetworkPolicy(  906): updateScreenOn: false
D/ContactMessageStore( 1239): start background delete task...
D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/ContactMessageStore( 1239): size: 0 , 0
D/ContactMessageStore( 1239): Background delete complete
W/Settings( 4167): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/LocationManagerService(  906): request 42356920 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
E/SmartNS_Utility( 4167): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4167): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4167): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4167): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4167): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 4167): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4167): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4167):  defaultType:0
,I/PhoneStatusBar( 1116): removeHeadsNotification.gc: 53
W/ContextImpl( 4318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4318): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4318): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4318): getMobilePolicyEnabled, result = true
D/WifiService(  906): New client listening to asynchronous messages
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4214a1a0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4214a1a0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4214a1a0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4214a1a0
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41f26100 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41f26100 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1805): onScreenOff.
D/PMS     (  906): acquireWL(42786b60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
,D/PMS     (  906): releaseWL(42786b60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1805): onScreenOff
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1161): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1161): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1161): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1161): Add randomness: count=11 e,ntropy=5
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: DISCONNECTED -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000113811643
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000113811667
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000113811681
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 113811643, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 113811667, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 113811681, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42793488 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42793488 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42793488 target=com.android.internal.util.StateMachine$SmHandler }
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/AutoSetting( 1534): service - handleMessage() stop self
,D/AutoSetting( 1534): service - onDestroy() END
,D/AutoSetting( 1534): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3896
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3896:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3896
,D/AutoSetting( 1399): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1399): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4271aaa8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(427a38a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  906): BroadcastReceiver::onReceive-,
D/PMS     (  906): releaseWL(427a38a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...,
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1161): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1161): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1161): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 la,st_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1161): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1161): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1161): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
,I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000113811643
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000132065291
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-75
I/wpa_supplicant( 1161): tsf=0000000132065301
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000132065279
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 113811643, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 132065291, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 132065301, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 132065279, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1,
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1399): service - handleMessage() stop self
,D/AutoSetting( 1399): service - handleMessage() quit looper
,D/AutoSetting( 1399): service - onDestroy() END
D/PMS     (  906): acquireWL(427c2508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42410dd0: PendingIntentRecord{424b52f8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141107, Int=0
,D/Process (  906): killProcessQuiet, pid=4007
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4007:com.htc.updater/u0a84 (adj 15): empty #17
V/AlarmManager(  906): sending alarm PendingIntent{424b3050: PendingIntentRecord{424eeaf8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141312, Int=0
,I/ActivityManager(  906): Recipient 4007
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(427c7400): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1386/10028)
D/PMS     (  906): acquireWL(427caf50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1386 10028 null
D/PMS     (  906): releaseWL(427c2508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  906): releaseWL(427caf50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7bc6 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(427c7400): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1161): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1161): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1161): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1161): Add randomness: count=25 entropy=19
,D/wpa_supplicant( 1161): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1161): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000150304762
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000150304799
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000150304809
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000150304788
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 150304762, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 150304799, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 150304809, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 150304788, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000),
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/PMS     (  906): acquireWL(42811a20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=161340, Int=0
,D/PMS     (  906): releaseWL(42811a20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1161): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1161): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1161): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
,I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1161): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1161): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1161): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000168564779
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000168564816
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
,I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000168564828
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000168564805
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 168564779, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 168564816, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 168564828, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 168564805, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  906): acquireWL(4282b350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4282b350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428740b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{42072f78: PendingIntentRecord{426d9c88 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174146, Int=0
,D/PMS     (  906): releaseWL(428740b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028),
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1161): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1161): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1161): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1161): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000186844718
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000186844745
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000186844756
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412,
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000168564805
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 186844718, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 186844745, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 186844756, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 168564805, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4288f078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4288f078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available,
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1161): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1161): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1161): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1161): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000205074789
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000205074815
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000205074826
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 205074789, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 205074815, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000),
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 205074826, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter,
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  906): acquireWL(428aa868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=221340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428aa868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1161): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1161): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1161): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1161): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1161): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1161): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000223441362
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000223441401
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000223441411
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412,
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000223441389
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 223441362, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 223441401, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 223441411, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 223441389, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(428c4088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(428c4088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available,
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1161): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1161): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1161): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1161): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1161): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1161): Add randomness: count=63 entropy=57
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000241694930
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000241694968
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-71
I/wpa_supplicant( 1161): tsf=0000000241694978
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000241694957
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 241694930, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 241694968, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2412, timestamp: 241694978, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 241694957, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  906): acquireWL(428e25e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428e25e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1161): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1161): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1161): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1161): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1161): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1161): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1161): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1161): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (631) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000259924960
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000259924999
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-71
I/wpa_supplicant( 1161): tsf=0000000259925010
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000259924988
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000259925018
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 259924960, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 259924999, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2412, timestamp: 259925010, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 259924988, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 259925018, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1161): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1161): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1161): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1161): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1161): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1161): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1161): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1161): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (631) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000278249406
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000278249444
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000278249454
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000278249433
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000278249463
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 278249406, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 278249444, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 278249454, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 278249433, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 278249463, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (5) end of scan result ==,
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  906): acquireWL(41e99038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=281340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41e99038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41ed1238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(41ed1238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1161): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1161): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1161): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1161): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1161): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1161): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list -, type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1161): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-89
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1161): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1161): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1161): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1161): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1161): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1161): reply (776) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000278249406
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000296524045
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000296524055
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
,I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000296524034
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000296524076
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=6
I/wpa_supplicant( 1161): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-89
I/wpa_supplicant( 1161): tsf=0000000296524064
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 278249406, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 296524045, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 296524055, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 296524034, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 296524076, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 296524064, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(42548cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42548cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1161): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1161): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1161): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant(, 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1161): Add randomness: count=101 entropy=95
D/wpa_supplicant( 1161): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1161): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1161): reply (776) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000314764655
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000314764692
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000314764702
,I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000314764682
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000296524076
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=6
I/wpa_supplicant( 1161): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-89
I/wpa_supplicant( 1161): tsf=0000000296524064
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1161): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 314764655, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 314764692, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 314764702, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 314764682, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 296524076, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2437, timestamp: 296524064, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-89], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1161): Add randomness: count=105 entropy=99
D/wpa_supplicant( 1161): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1161): Add randomness: count=107 entropy=101
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_suppl,icant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=108 entropy=102
D/wpa_supplicant( 1161): Add randomness: count=109 entropy=103
D/wpa_supplicant( 1161): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1161): Add randomness: count=111 entropy=105
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000333122013
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000333122050
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-87
I/wpa_supplicant( 1161): tsf=0000000333122060
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000333122039
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 333122013, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 333122050, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 333122060, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 333122039, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/PMS     (  906): acquireWL(4281d820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=341340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4281d820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(424ae460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(424ae460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1161): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1161): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1161): Add randomness: count=115 entropy=109
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_sup,plicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1161): Add randomness: count=117 entropy=111
D/wpa_supplicant( 1161): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1161): Add randomness: count=119 entropy=113
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000351374132
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000351374169
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-74
,I/wpa_supplicant( 1161): tsf=0000000351374181
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000351374159
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 351374132, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 351374169, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 351374181, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 351374159, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1386): GoogleAccountDataService.getToken()
,W/GLSActivity( 1386): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1386): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1386): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1386): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1386): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1386): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1386): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1386): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1386): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1386): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1386): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/PlayEventLogger( 4109): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4109): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4109): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4109): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4109): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4109): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4109): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4109): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41f31000 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 12 3 12
,D/libc    ( 4109): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4109): [NET] getaddrinfo-,err=8
D/libc    ( 4109): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4109): [NET] getaddrinfo-, 1
,D/libc    ( 4109): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5b83 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4109): [NET] getaddrinfo_proxy-, success
I/global  ( 4109): call createSocket() return a new socket.
D/libc    ( 4109): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4109): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4109): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4109): [NET] getaddrinfo-,err=8
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1161): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1161): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1161): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1161): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161),: send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=125 entropy=119
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1161): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1161): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1161): Add randomness: count=128 entropy=122
D/wpa_supplicant( 1161): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (636) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000369644763
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000369644800
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000369644810
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000369644789
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000369644819
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC4688432
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 369644763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 369644800, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 369644810, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 369644789, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 369644819, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42363760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  906): releaseWL(42363760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1161): Add randomness: count=131 entropy=125
D/wpa_supplicant( 1161): Add randomness: count=132 entropy=126
D/wpa_supplicant( 1161): Add randomness: count=133 entropy=127
D/wpa_supplicant( 1161): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1161): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1161): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_i,e_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=137 entropy=131
D/wpa_supplicant( 1161): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1161): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1161): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1161): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1161): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1161): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBro,adcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (902) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000387862128
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000387862167
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000387862177
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000387862155
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000387862188
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC4688432
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=8
I/wpa_supplicant( 1161): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000387862198
I/wpa_supplicant( 1161): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000387862209
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 387862128, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 387862167, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 387862177, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 387862155, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 387862188, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 387862198, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 387862209, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(427d4f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=401340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427d4f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1161): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1161): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1161): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1161): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1161): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1161): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_i,e_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 6: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1161): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1161): Add randomness: count=153 entropy=147
D/wpa_supplicant( 1161): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1161): Add randomness: count=155 entropy=149
D/wpa_supplicant( 1161): Add randomness: count=156 entropy=150
D/wpa_supplicant( 1161): Add randomness: count=157 entropy=151
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (902) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000406124818
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000406124856
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000406124866
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000406124845
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000406124875
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC4688432
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=8
I/wpa_supplicant( 1161): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000406124885
I/wpa_supplicant( 1161): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000406124895
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 406124818, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 406124856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 406124866, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 406124845, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 406124875, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 406124885, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 406124895, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 7 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(427a51e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(427a51e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=158 entropy=152
D/wpa_supplicant( 1161): Add randomness: count=159 entropy=153
D/wpa_supplicant( 1161): Add randomness: count=160 entropy=154
D/wpa_supplicant( 1161): Add randomness: count=161 entropy=155
D/wpa_supplicant( 1161): Add randomness: count=162 entropy=156
D/wpa_supplicant( 1161): Add randomness: count=163 entropy=157
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not ,restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=164 entropy=158
D/wpa_supplicant( 1161): Add randomness: count=165 entropy=159
D/wpa_supplicant( 1161): Add randomness: count=166 entropy=160
D/wpa_supplicant( 1161): Add randomness: count=167 entropy=161
D/wpa_supplicant( 1161): Add randomness: count=168 entropy=162
D/wpa_supplicant( 1161): Add randomness: count=169 entropy=163
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (902) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000424305171
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412,
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000424305209
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000424305219
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000424305199
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000406124875
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC4688432
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=8
I/wpa_supplicant( 1161): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1161): freq=2462,
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000424305228
I/wpa_supplicant( 1161): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000424305238
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 424305171, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 424305209, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 424305219, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 424305199, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 406124875, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 424305228, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 424305238, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 7 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42364698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42364698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=170 entropy=164
D/wpa_supplicant( 1161): Add randomness: count=171 entropy=165
D/wpa_supplicant( 1161): Add randomness: count=172 entropy=166
D/wpa_supplicant( 1161): Add randomness: count=173 entropy=167
D/wpa_supplicant( 1161): Add randomness: count=174 entropy=168
D/wpa_supplicant( 1161): Add randomness: count=175 entropy=169
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not ,restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=176 entropy=170
D/wpa_supplicant( 1161): Add randomness: count=177 entropy=171
D/wpa_supplicant( 1161): Add randomness: count=178 entropy=172
D/wpa_supplicant( 1161): Add randomness: count=179 entropy=173
D/wpa_supplicant( 1161): Add randomness: count=180 entropy=174
D/wpa_supplicant( 1161): Add randomness: count=181 entropy=175
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  906): getDiscoveryDongleList
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (755) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
,I/wpa_supplicant( 1161): tsf=0000000442554770
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000442554808
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000442554818
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000442554797
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=8
I/wpa_supplicant( 1161): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000442554827
I/wpa_supplicant( 1161): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000442554837
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 442554770, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 442554808, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 442554818, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 442554797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 442554827, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 442554837, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=182 entropy=176
D/wpa_supplicant( 1161): Add randomness: count=183 entropy=177
D/wpa_supplicant( 1161): Add randomness: count=184 entropy=178
D/wpa_supplicant( 1161): Add randomness: count=185 entropy=179
D/wpa_supplicant( 1161): Add randomness: count=186 entropy=180
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplican,t( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=187 entropy=181
D/wpa_supplicant( 1161): Add randomness: count=188 entropy=182
D/wpa_supplicant( 1161): Add randomness: count=189 entropy=183
D/wpa_supplicant( 1161): Add randomness: count=190 entropy=184
D/wpa_supplicant( 1161): Add randomness: count=191 entropy=185
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (755) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000460882372
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000460882398
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000460882411
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====,
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000442554797
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=8
I/wpa_supplicant( 1161): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000442554827
I/wpa_supplicant( 1161): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
,I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-90
I/wpa_supplicant( 1161): tsf=0000000460882420
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 460882372, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 460882398, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 460882411, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 442554797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 442554827, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 460882420, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4287c5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=461340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4287c5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=192 entropy=186
D/wpa_supplicant( 1161): Add randomness: count=193 entropy=187
D/wpa_supplicant( 1161): Add randomness: count=194 entropy=188
D/wpa_supplicant( 1161): Add randomness: count=195 entropy=189
D/wpa_supplicant( 1161): Add randomness: count=196 entropy=190
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplican,t( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=197 entropy=191
D/wpa_supplicant( 1161): Add randomness: count=198 entropy=192
D/wpa_supplicant( 1161): Add randomness: count=199 entropy=193
D/wpa_supplicant( 1161): Add randomness: count=200 entropy=194
D/wpa_supplicant( 1161): Add randomness: count=201 entropy=195
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (642) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000479144811
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====,
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000479144838
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000479144849
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=8
I/wpa_supplicant( 1161): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1161): freq=2462,
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000442554827
I/wpa_supplicant( 1161): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-90
I/wpa_supplicant( 1161): tsf=0000000479144858
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 479144811, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 479144838, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 479144849, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 442554827, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 479144858, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 5 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(428253d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(428253d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=202 entropy=196
D/wpa_supplicant( 1161): Add randomness: count=203 entropy=197
D/wpa_supplicant( 1161): Add randomness: count=204 entropy=198
D/wpa_supplicant( 1161): Add randomness: count=205 entropy=199
D/wpa_supplicant( 1161): Add randomness: count=206 entropy=200
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/w,pa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
I/wpa_supplicant( 1161): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=207 entropy=201
D/wpa_supplicant( 1161): Add randomness: count=208 entropy=202
D/wpa_supplicant( 1161): Add randomness: count=209 entropy=203
D/wpa_supplicant( 1161): Add randomness: count=210 entropy=204
D/wpa_supplicant( 1161): Add randomness: count=211 entropy=205
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (642) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000497151771
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): fr,eq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000497151797
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000497151809
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=8
I/wpa_supplicant( 1161): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000442554827
I/wpa_supplicant( 1161): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-90
I/wpa_supplicant( 1161): tsf=0000000497151819
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 497151771, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 497151797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 497151809, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 442554827, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 497151819, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=212 entropy=206
D/wpa_supplicant( 1161): Add randomness: count=213 entropy=207
D/wpa_supplicant( 1161): Add randomness: count=214 entropy=208
D/wpa_supplicant( 1161): Add randomness: count=215 entropy=209
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=216 entropy=210
D/wpa_supplicant( 1161): Add randomness: count=217 entropy=211
D/wpa_supplicant( 1161): Add randomness: count=218 entropy=212
D/wpa_supplicant( 1161): Add randomness: count=219 entropy=213
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (756) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000515502347
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000515502386
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000515502398
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=8
I/wpa_supplicant( 1161): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000442554827
I/wpa_supplicant( 1161): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-90
I/wpa_supplicant( 1161): tsf=0000000497151819
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=10
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000515502374
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 515502347, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 515502386, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 515502398, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 442554827, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 497151819, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 515502374, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42908988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=521340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42908988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(4290ac48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4290ac48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=220 entropy=214
D/wpa_supplicant( 1161): Add randomness: count=221 entropy=215
D/wpa_supplicant( 1161): Add randomness: count=222 entropy=216
D/wpa_supplicant( 1161): Add randomness: count=223 entropy=217
D/wpa_supplicant( 1161): Add randomness: count=224 entropy=218
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,1): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=225 entropy=219
D/wpa_supplicant( 1161): Add randomness: count=226 entropy=220
D/wpa_supplicant( 1161): Add randomness: count=227 entropy=221
D/wpa_supplicant( 1161): Add randomness: count=228 entropy=222
D/wpa_supplicant( 1161): Add randomness: count=229 entropy=223
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (632) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000515502347
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000533784815
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000533784825
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000533784834
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=10
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000533784804
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 515502347, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 533784815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 533784825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 533784834, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 533784804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(4292c628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/PMS     (  906): releaseWL(4292c628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=230 entropy=224
D/wpa_supplicant( 1161): Add randomness: count=231 entropy=225
D/wpa_supplicant( 1161): Add randomness: count=232 entropy=226
D/wpa_supplicant( 1161): Add randomness: count=233 entropy=227
D/wpa_supplicant( 1161): Add randomness: count=234 entropy=228
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,1): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=235 entropy=229
D/wpa_supplicant( 1161): Add randomness: count=236 entropy=230
D/wpa_supplicant( 1161): Add randomness: count=237 entropy=231
D/wpa_supplicant( 1161): Add randomness: count=238 entropy=232
D/wpa_supplicant( 1161): Add randomness: count=239 entropy=233
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (632) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000552025141
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000552025180
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000552025189
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000552025198
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=10
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000552025167
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 552025141, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 552025180, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 552025189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 552025198, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 552025167, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=240 entropy=234
D/wpa_supplicant( 1161): Add randomness: count=241 entropy=235
D/wpa_supplicant( 1161): Add randomness: count=242 entropy=236
D/wpa_supplicant( 1161): Add randomness: count=243 entropy=237
D/wpa_supplicant( 1161): Add randomness: count=244 entropy=238
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,1): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=245 entropy=239
D/wpa_supplicant( 1161): Add randomness: count=246 entropy=240
D/wpa_supplicant( 1161): Add randomness: count=247 entropy=241
D/wpa_supplicant( 1161): Add randomness: count=248 entropy=242
D/wpa_supplicant( 1161): Add randomness: count=249 entropy=243
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (632) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000570372056
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000570372092
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000570372102
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000570372110
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=10
,I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000570372081
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 570372056, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 570372092, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 570372102, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 570372110, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 570372081, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1,
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42968ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=581340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42968ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=250 entropy=244
D/wpa_supplicant( 1161): Add randomness: count=251 entropy=245
D/wpa_supplicant( 1161): Add randomness: count=252 entropy=246
D/wpa_supplicant( 1161): Add randomness: count=253 entropy=247
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=254 entropy=248
D/wpa_supplicant( 1161): Add randomness: count=255 entropy=249
D/wpa_supplicant( 1161): Add randomness: count=256 entropy=250
D/wpa_supplicant( 1161): Add randomness: count=257 entropy=251
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (632) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000588604947
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000588604985
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000588604995
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000570372110
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=10
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000588604974
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 588604947, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 588604985, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 588604995, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 570372110, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 588604974, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42985b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42985b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=258 entropy=252
D/wpa_supplicant( 1161): Add randomness: count=259 entropy=253
D/wpa_supplicant( 1161): Add randomness: count=260 entropy=254
D/wpa_supplicant( 1161): Add randomness: count=261 entropy=255
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0,
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0,
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
,I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
,I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=262 entropy=256
D/wpa_supplicant( 1161): Add randomness: count=263 entropy=257
D/wpa_supplicant( 1161): Add randomness: count=264 entropy=258
D/wpa_supplicant( 1161): Add randomness: count=265 entropy=259
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (632) for get BSS: id=0
,I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000606874945
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000606874972
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000606874983
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000606874992
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=10
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000588604974
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 606874945, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 606874972, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 606874983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 606874992, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 588604974, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42998b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42998b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1239): sku_id=99
D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=266 entropy=260
D/wpa_supplicant( 1161): Add randomness: count=267 entropy=261
D/wpa_supplicant( 1161): Add randomness: count=268 entropy=262
D/wpa_supplicant( 1161): Add randomness: count=269 entropy=263
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d,4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=270 entropy=264
D/wpa_supplicant( 1161): Add randomness: count=271 entropy=265
D/wpa_supplicant( 1161): Add randomness: count=272 entropy=266
D/wpa_supplicant( 1161): Add randomness: count=273 entropy=267
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (518) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000625181901
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000625181928
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000625181939
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000625181949
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 625181901, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 625181928, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 625181939, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 625181949, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(426ca0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=641340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426ca0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=274 entropy=268
D/wpa_supplicant( 1161): Add randomness: count=275 entropy=269
D/wpa_supplicant( 1161): Add randomness: count=276 entropy=270
D/wpa_supplicant( 1161): Add randomness: count=277 entropy=271
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d,4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=278 entropy=272
D/wpa_supplicant( 1161): Add randomness: count=279 entropy=273
D/wpa_supplicant( 1161): Add randomness: count=280 entropy=274
D/wpa_supplicant( 1161): Add randomness: count=281 entropy=275
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (518) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000643351719
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000643351745
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000643351757
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000643351765
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 643351719, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 643351745, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 643351757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 643351765, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42220da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42220da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=282 entropy=276
D/wpa_supplicant( 1161): Add randomness: count=283 entropy=277
D/wpa_supplicant( 1161): Add randomness: count=284 entropy=278
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=285 entropy=279
D/wpa_supplica,nt( 1161): Add randomness: count=286 entropy=280
D/wpa_supplicant( 1161): Add randomness: count=287 entropy=281
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (518) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000661564706
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000661564733
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000661564744
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=9
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000643351765
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 661564706, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 661564733, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 661564744, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 643351765, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/Process (  906): killProcessQuiet, pid=3724
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3724:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3724
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42748f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42748f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=288 entropy=282
D/wpa_supplicant( 1161): Add randomness: count=289 entropy=283
D/wpa_supplicant( 1161): Add randomness: count=290 entropy=284
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
,I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=291 entropy=285
D/wpa_supplicant( 1161): Add randomness: count=292 entropy=286
D/wpa_supplicant( 1161): Add randomness: count=293 entropy=287
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000679796481
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000679796507
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000679796519
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiP2pService(  906): InactiveState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 679796481, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  906): DefaultState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 679796507, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 679796519, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=294 entropy=288
D/wpa_supplicant( 1161): Add randomness: count=295 entropy=289
D/wpa_supplicant( 1161): Add randomness: count=296 entropy=290
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=297 entropy=291
D/wpa_supplica,nt( 1161): Add randomness: count=298 entropy=292
D/wpa_supplicant( 1161): Add randomness: count=299 entropy=293
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000698092109
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000698092135
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000698092147
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 698092109, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 698092135, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 698092147, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42672c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=701340, Int=0
,D/PMS     (  906): releaseWL(42672c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4265ab70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4265ab70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=300 entropy=294
D/wpa_supplicant( 1161): Add randomness: count=301 entropy=295
D/wpa_supplicant( 1161): Add randomness: count=302 entropy=296
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplica,nt( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=303 entropy=297
D/wpa_supplicant( 1161): Add randomness: count=304 entropy=298
D/wpa_supplicant( 1161): Add randomness: count=305 entropy=299
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000698092109
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000716321972
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-75
I/wpa_supplicant( 1161): tsf=0000000716321983
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 698092109, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 716321972, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 716321983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiP2pService(  906): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(425c4a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/BatteryService(  906): n_update end
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(425c4a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=306 entropy=300
D/wpa_supplicant( 1161): Add randomness: count=307 entropy=301
D/wpa_supplicant( 1161): Add randomness: count=308 entropy=302
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=309 entropy=303
D/wpa_supplica,nt( 1161): Add randomness: count=310 entropy=304
D/wpa_supplicant( 1161): Add randomness: count=311 entropy=305
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000734451678
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000734451704
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000734451715
,I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 734451678, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 734451704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 734451715, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=312 entropy=306
D/wpa_supplicant( 1161): Add randomness: count=313 entropy=307
D/wpa_supplicant( 1161): Add randomness: count=314 entropy=308
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=315 entropy=309
D/wpa_supplica,nt( 1161): Add randomness: count=316 entropy=310
D/wpa_supplicant( 1161): Add randomness: count=317 entropy=311
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000752801785
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000752801810
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000752801822
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WirelessDisplayService(  906): getDiscoveryDongleList
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 752801785, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 752801810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 752801822, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426e52b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=761340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426e52b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=318 entropy=312
D/wpa_supplicant( 1161): Add randomness: count=319 entropy=313
D/wpa_supplicant( 1161): Add randomness: count=320 entropy=314
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=321 entropy=315
D/wpa_supplica,nt( 1161): Add randomness: count=322 entropy=316
D/wpa_supplicant( 1161): Add randomness: count=323 entropy=317
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000771034817
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000771034843
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000771034854
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 771034817, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 771034843, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 771034854, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/PMS     (  906): acquireWL(42965ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42965ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=324 entropy=318
D/wpa_supplicant( 1161): Add randomness: count=325 entropy=319
D/wpa_supplicant( 1161): Add randomness: count=326 entropy=320
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=327 entropy=321
D/wpa_supplica,nt( 1161): Add randomness: count=328 entropy=322
D/wpa_supplicant( 1161): Add randomness: count=329 entropy=323
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000789191981
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000789192007
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====,
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000789192019
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 789191981, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 789192007, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 789192019, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4295e500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4295e500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=330 entropy=324
D/wpa_supplicant( 1161): Add randomness: count=331 entropy=325
D/wpa_supplicant( 1161): Add randomness: count=332 entropy=326
D/wpa_supplicant( 1161): Add randomness: count=333 entropy=327
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=334 entropy=328
D/wpa_supplicant( 1161): Add randomness: count=335 entropy=329
D/wpa_supplicant( 1161): Add randomness: count=336 entropy=330
D/wpa_supplicant( 1161): Add randomness: count=337 entropy=331
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000807202047
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000807202085
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000807202095
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=11
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000807202072
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 807202047, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 807202085, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 807202095, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 807202072, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(429918d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=821340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429918d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=338 entropy=332
D/wpa_supplicant( 1161): Add randomness: count=339 entropy=333
D/wpa_supplicant( 1161): Add randomness: count=340 entropy=334
D/wpa_supplicant( 1161): Add randomness: count=341 entropy=335
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=342 entropy=336
D/wpa_supplicant( 1161): Add randomness: count=343 entropy=337
D/wpa_supplicant( 1161): Add randomness: count=344 entropy=338
D/wpa_supplicant( 1161): Add randomness: count=345 entropy=339
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (490) for get BSS: id=0,
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000807202047
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000825181737
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-75
I/wpa_supplicant( 1161): tsf=0000000825181747
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=11
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000825181725
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 807202047, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 825181737, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 825181747, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 825181725, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=346 entropy=340
D/wpa_supplicant( 1161): Add randomness: count=347 entropy=341
D/wpa_supplicant( 1161): Add randomness: count=348 entropy=342
D/wpa_supplicant( 1161): Add randomness: count=349 entropy=343
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=350 entropy=344
D/wpa_supplicant( 1161): Add randomness: count=351 entropy=345
D/wpa_supplicant( 1161): Add randomness: count=352 entropy=346
D/wpa_supplicant( 1161): Add randomness: count=353 entropy=347
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000843529657
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000843529694
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161),: tsf=0000000843529704
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=11
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000843529684
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 843529657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 843529694, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 843529704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 843529684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42646d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42646d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=354 entropy=348
D/wpa_supplicant( 1161): Add randomness: count=355 entropy=349
D/wpa_supplicant( 1161): Add randomness: count=356 entropy=350
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=357 entropy=351
D/wpa_supplica,nt( 1161): Add randomness: count=358 entropy=352
D/wpa_supplicant( 1161): Add randomness: count=359 entropy=353
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000861764899
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000861764925
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000861764936,
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=11
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000843529684
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 861764899, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 861764925, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 861764936, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 843529684, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=360 entropy=354
D/wpa_supplicant( 1161): Add randomness: count=361 entropy=355
D/wpa_supplicant( 1161): Add randomness: count=362 entropy=356
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
,I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=363 entropy=357
D/wpa_supplicant( 1161): Add randomness: count=364 entropy=358
D/wpa_supplicant( 1161): Add randomness: count=365 entropy=359
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
,I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000880091770
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57,
I/wpa_supplicant( 1161): tsf=0000000880091796
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000880091807
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 880091770, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 880091796, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 880091807, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4292cbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=881340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4292cbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=366 entropy=360
D/wpa_supplicant( 1161): Add randomness: count=367 entropy=361
D/wpa_supplicant( 1161): Add randomness: count=368 entropy=362
D/wpa_supplicant( 1161): Add randomness: count=369 entropy=363
D/wpa_supplicant( 1161): Add randomness: count=370 entropy=364
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,1): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=371 entropy=365
D/wpa_supplicant( 1161): Add randomness: count=372 entropy=366
D/wpa_supplicant( 1161): Add randomness: count=373 entropy=367
D/wpa_supplicant( 1161): Add randomness: count=374 entropy=368
D/wpa_supplicant( 1161): Add randomness: count=375 entropy=369
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (633) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000898354815
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000898354853
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-75
I/wpa_supplicant( 1161): tsf=0000000898354863
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
,I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=12
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000898354842
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=13
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000898354872
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 898354815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 898354853, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 898354863, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 898354842, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 898354872, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4292dfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4292dfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=376 entropy=370
D/wpa_supplicant( 1161): Add randomness: count=377 entropy=371
D/wpa_supplicant( 1161): Add randomness: count=378 entropy=372
D/wpa_supplicant( 1161): Add randomness: count=379 entropy=373
D/wpa_supplicant( 1161): Add randomness: count=380 entropy=374
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,1): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=381 entropy=375
D/wpa_supplicant( 1161): Add randomness: count=382 entropy=376
D/wpa_supplicant( 1161): Add randomness: count=383 entropy=377
D/wpa_supplicant( 1161): Add randomness: count=384 entropy=378
D/wpa_supplicant( 1161): Add randomness: count=385 entropy=379
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (633) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000916351769
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000916351806
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-75
I/wpa_supplicant( 1161): tsf=0000000916351816
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=12
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000916351795
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=13
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000916351825
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 916351769, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 916351806, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 916351816, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 916351795, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 916351825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=386 entropy=380
D/wpa_supplicant( 1161): Add randomness: count=387 entropy=381
D/wpa_supplicant( 1161): Add randomness: count=388 entropy=382
D/wpa_supplicant( 1161): Add randomness: count=389 entropy=383
D/wpa_supplicant( 1161): Add randomness: count=390 entropy=384
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 116,1): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1161): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=391 entropy=385
D/wpa_supplicant( 1161): Add randomness: count=392 entropy=386
D/wpa_supplicant( 1161): Add randomness: count=393 entropy=387
D/wpa_supplicant( 1161): Add randomness: count=394 entropy=388
D/wpa_supplicant( 1161): Add randomness: count=395 entropy=389
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (633) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
,I/wpa_supplicant( 1161): tsf=0000000934670654
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000934670691
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000934670703
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=12
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000934670680
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=13
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000934670711
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 934670654, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 934670691, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 934670703, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 934670680, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 934670711, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4292bb20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=941340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4292bb20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(42907130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(42907130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=396 entropy=390
D/wpa_supplicant( 1161): Add randomness: count=397 entropy=391
D/wpa_supplicant( 1161): Add randomness: count=398 entropy=392
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=399 entropy=393
D/wpa_supplica,nt( 1161): Add randomness: count=400 entropy=394
D/wpa_supplicant( 1161): Add randomness: count=401 entropy=395
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (633) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000952933454
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000952933476
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000952933487
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=12
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000934670680
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=13
I/wpa_supplicant( 1161): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1161): freq=2462
I/wpa_supplicant( 1161): level=-92
I/wpa_supplicant( 1161): tsf=0000000934670711
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC0039325
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 952933454, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 952933476, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 952933487, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 934670680, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 934670711, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=402 entropy=396
D/wpa_supplicant( 1161): Add randomness: count=403 entropy=397
D/wpa_supplicant( 1161): Add randomness: count=404 entropy=398
D/wpa_supplicant( 1161): Add randomness: count=405 entropy=399
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=406 entropy=400
D/wpa_supplicant( 1161): Add randomness: count=407 entropy=401
D/wpa_supplicant( 1161): Add randomness: count=408 entropy=402
D/wpa_supplicant( 1161): Add randomness: count=409 entropy=403
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000971194809
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000971194847
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000971194857
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_suppli,cant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=12
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000971194835
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 971194809, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 971194847, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 971194857, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 971194835, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(427abe60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(427abe60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=410 entropy=404
D/wpa_supplicant( 1161): Add randomness: count=411 entropy=405
D/wpa_supplicant( 1161): Add randomness: count=412 entropy=406
D/wpa_supplicant( 1161): Add randomness: count=413 entropy=407
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=414 entropy=408
D/wpa_supplicant( 1161): Add randomness: count=415 entropy=409
D/wpa_supplicant( 1161): Add randomness: count=416 entropy=410
D/wpa_supplicant( 1161): Add randomness: count=417 entropy=411
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000971194809
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000989529696
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2,
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000000989529706
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=12
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000989529686
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiP2pService(  906): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 971194809, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 989529696, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 989529706, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 989529686, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42882698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1001340, Int=0
,D/PMS     (  906): releaseWL(42882698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=418 entropy=412
D/wpa_supplicant( 1161): Add randomness: count=419 entropy=413
D/wpa_supplicant( 1161): Add randomness: count=420 entropy=414
D/wpa_supplicant( 1161): Add randomness: count=421 entropy=415
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=422 entropy=416
D/wpa_supplicant( 1161): Add randomness: count=423 entropy=417
D/wpa_supplicant( 1161): Add randomness: count=424 entropy=418
D/wpa_supplicant( 1161): Add randomness: count=425 entropy=419
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
,I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001007724732
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001007724769
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001007724779
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=12
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001007724757
,I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1007724732, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1007724769, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1007724779, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 1007724757, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4280cbd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e34140: PendingIntentRecord{42494648 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784108, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42548b50: PendingIntentRecord{424f24f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=927991, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4381 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42669ec0: PendingIntentRecord{4264f788 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454950498753, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{424efc38: PendingIntentRecord{4253ce78 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454950794879, Int=1800000
V/AlarmManager(  906): sending alarm PendingIntent{41b5fc20: PendingIntentRecord{425e69f8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454951219305, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{4244cb98: PendingIntentRecord{4264b390 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454951289922, Int=0
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(427f2d68): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1386 10028 null
,D/PMS     (  906): releaseWL(427f2d68): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(42944ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1386 10028 null
,D/PMS     (  906): acquireWL(429455c0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(42944ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(42947288): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(429455c0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,W/ContextImpl( 4318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/EventLogService( 1223): Aggregate from 1454950332538 (log), 1454948994826 (data)
,D/PowerUsageService( 4318): call getInstance()
,D/SmartSyncUtils( 4318): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4318): MY_DEBUG = false
D/PMS     (  906): releaseWL(4280cbd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(4294a7f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4318 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4318): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4318): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4318): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4318): SettingOnTime = 1454979600000, randomSettingOnTime = 1454977422000
,D/SmartSyncScreenOnOffTimeReceiver( 4318): SettingOffTime = 1454976000000, randomSettingOffTime = 1454976294000
,D/SmartSyncScreenOnOffTimeReceiver( 4318): bDayMode = false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4381/10047)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
D/SmartSyncScreenOnOffTimeReceiver( 4318): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4318): bNightModeTurnOffOnce = false
D/PMS     (  906): releaseWL(4294a7f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): releaseWL(42947288): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,I/dalvikvm-heap(  906): Grow heap (frag case) to 17.927MB for 148820-byte allocation
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=4062
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4062:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4062
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(425b1d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(425b1d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(423b23e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1386 10028 null
,D/GCM     ( 1386): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1386/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1386/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1386/10028)
,D/PMS     (  906): acquireWL(4259c5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1386 10028 null
,D/PMS     (  906): releaseWL(4259c5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): releaseWL(423b23e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=426 entropy=420
D/wpa_supplicant( 1161): Add randomness: count=427 entropy=421
D/wpa_supplicant( 1161): Add randomness: count=428 entropy=422
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=429 entropy=423
D/wpa_supplicant( 1161): Add randomness: count=430 entropy=424
D/wpa_supplicant( 1161): Add randomness: count=431 entropy=425
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001025954757
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001025954783
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-86
I/wpa_supplicant( 1161): tsf=0000001025954794,
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=12
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001007724757
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1025954757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1025954783, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 1025954794, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 1007724757, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42753b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(42753b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=432 entropy=426
D/wpa_supplicant( 1161): Add randomness: count=433 entropy=427
D/wpa_supplicant( 1161): Add randomness: count=434 entropy=428
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=435 entropy=429
D/wpa_supplica,nt( 1161): Add randomness: count=436 entropy=430
D/wpa_supplicant( 1161): Add randomness: count=437 entropy=431
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
,I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001044214764
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001044214791
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-75
I/wpa_supplicant( 1161): tsf=0000001044214801
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1044214764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1044214791, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1044214801, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults,
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(42729210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1061340, Int=0
,D/PMS     (  906): releaseWL(42729210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=438 entropy=432
D/wpa_supplicant( 1161): Add randomness: count=439 entropy=433
D/wpa_supplicant( 1161): Add randomness: count=440 entropy=434
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=441 entropy=435
D/wpa_supplica,nt( 1161): Add randomness: count=442 entropy=436
D/wpa_supplicant( 1161): Add randomness: count=443 entropy=437
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001062559703
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001062559729
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001062559740
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1062559703, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1062559729, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1062559740, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426bfe48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426bfe48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=444 entropy=438
D/wpa_supplicant( 1161): Add randomness: count=445 entropy=439
D/wpa_supplicant( 1161): Add randomness: count=446 entropy=440
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=447 entropy=441
D/wpa_supplica,nt( 1161): Add randomness: count=448 entropy=442
D/wpa_supplicant( 1161): Add randomness: count=449 entropy=443
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001080814739
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001080814765
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001062559740
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1080814739, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1080814765, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1062559740, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42659e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(42659e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=450 entropy=444
D/wpa_supplicant( 1161): Add randomness: count=451 entropy=445
D/wpa_supplicant( 1161): Add randomness: count=452 entropy=446
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=453 entropy=447
D/wpa_supplica,nt( 1161): Add randomness: count=454 entropy=448
D/wpa_supplicant( 1161): Add randomness: count=455 entropy=449
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001099074620
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
,I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001099074647
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001099074658
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
,I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1099074620, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1099074647, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1099074658, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=456 entropy=450
D/wpa_supplicant( 1161): Add randomness: count=457 entropy=451
D/wpa_supplicant( 1161): Add randomness: count=458 entropy=452
D/wpa_supplicant( 1161): Add randomness: count=459 entropy=453
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=460 entropy=454
D/wpa_supplicant( 1161): Add randomness: count=461 entropy=455
D/wpa_supplicant( 1161): Add randomness: count=462 entropy=456
D/wpa_supplicant( 1161): Add randomness: count=463 entropy=457
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001117401230
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001117401268
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001117401278
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=14
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000001117401256
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1117401230, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1117401268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1117401278, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1117401256, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WirelessDisplayService(  906): getDiscoveryDongleList
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000),
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/PMS     (  906): acquireWL(427ca5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1121339, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427ca5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(4270e4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4270e4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=464 entropy=458
D/wpa_supplicant( 1161): Add randomness: count=465 entropy=459
D/wpa_supplicant( 1161): Add randomness: count=466 entropy=460
D/wpa_supplicant( 1161): Add randomness: count=467 entropy=461
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=468 entropy=462
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): Add randomness: count=469 entropy=463
D/wpa_supplicant( 1161): Add randomness: count=470 entropy=464
D/wpa_supplicant( 1161): Add randomness: count=471 entropy=465
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001135644805
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001135644843
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001135644853
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=14
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000001135644832
I/wpa_supplicant( 1161): flags=[WPA2,-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1135644805, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1135644843, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1135644853, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1135644832, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(428f5e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428f5e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=472 entropy=466
D/wpa_supplicant( 1161): Add randomness: count=473 entropy=467
D/wpa_supplicant( 1161): Add randomness: count=474 entropy=468
D/wpa_supplicant( 1161): Add randomness: count=475 entropy=469
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=476 entropy=470
D/wpa_supplicant( 1161): Add randomness: count=477 entropy=471
D/wpa_supplicant( 1161): Add randomness: count=478 entropy=472
D/wpa_supplicant( 1161): Add randomness: count=479 entropy=473
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001153931831
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001153931868
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001153931878
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=14
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000001153931858
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1153931831, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1153931868, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1153931878, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1153931858, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=480 entropy=474
D/wpa_supplicant( 1161): Add randomness: count=481 entropy=475
D/wpa_supplicant( 1161): Add randomness: count=482 entropy=476
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=483 entropy=477
D/wpa_supplica,nt( 1161): Add randomness: count=484 entropy=478
D/wpa_supplicant( 1161): Add randomness: count=485 entropy=479
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001172182353
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001172182380
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001172182393
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=14
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000001153931858
I/wpa_supplicant(, 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1172182353, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1172182380, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1172182393, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1153931858, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426e2220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1181340, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426e2220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=486 entropy=480
D/wpa_supplicant( 1161): Add randomness: count=487 entropy=481
D/wpa_supplicant( 1161): Add randomness: count=488 entropy=482
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=489 entropy=483
D/wpa_supplica,nt( 1161): Add randomness: count=490 entropy=484
D/wpa_supplicant( 1161): Add randomness: count=491 entropy=485
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001190425059
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001190425085
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001190425096
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1190425059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1190425085, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1190425096, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4290c920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4290c920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=492 entropy=486
D/wpa_supplicant( 1161): Add randomness: count=493 entropy=487
D/wpa_supplicant( 1161): Add randomness: count=494 entropy=488
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=495 entropy=489
D/wpa_supplica,nt( 1161): Add randomness: count=496 entropy=490
D/wpa_supplicant( 1161): Add randomness: count=497 entropy=491
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001208571882
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001208571908
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001208571920
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WirelessDisplayService(  906): getDiscoveryDongleList
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1208571882, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1208571908, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1208571920, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/PMS     (  906): acquireWL(427346f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(427346f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=498 entropy=492
D/wpa_supplicant( 1161): Add randomness: count=499 entropy=493
D/wpa_supplicant( 1161): Add randomness: count=500 entropy=494
D/wpa_supplicant( 1161): Add randomness: count=501 entropy=495
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=502 entropy=496
D/wpa_supplicant( 1161): Add randomness: count=503 entropy=497
D/wpa_supplicant( 1161): Add randomness: count=504 entropy=498
D/wpa_supplicant( 1161): Add randomness: count=505 entropy=499
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001226814737
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001226814777
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001226814787
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=15
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000001226814763
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1226814737, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1226814777, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1226814787, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1226814763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(428aab70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42399a18: PendingIntentRecord{423a6cb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1241340, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428aab70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=506 entropy=500
D/wpa_supplicant( 1161): Add randomness: count=507 entropy=501
D/wpa_supplicant( 1161): Add randomness: count=508 entropy=502
D/wpa_supplicant( 1161): Add randomness: count=509 entropy=503
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=510 entropy=504
D/wpa_supplicant( 1161): Add randomness: count=511 entropy=505
D/wpa_supplicant( 1161): Add randomness: count=512 entropy=506
D/wpa_supplicant( 1161): Add randomness: count=513 entropy=507
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001244792087
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001244792124
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001244792134
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=15
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000001244792113
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1244792087, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1244792124, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1244792134, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1244792113, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4296c6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4296c6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=514 entropy=508
D/wpa_supplicant( 1161): Add randomness: count=515 entropy=509
D/wpa_supplicant( 1161): Add randomness: count=516 entropy=510
D/wpa_supplicant( 1161): Add randomness: count=517 entropy=511
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:a,a:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=518 entropy=512
D/wpa_supplicant( 1161): Add randomness: count=519 entropy=513
D/wpa_supplicant( 1161): Add randomness: count=520 entropy=514
D/wpa_supplicant( 1161): Add randomness: count=521 entropy=515
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001263044830
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001263044867
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001263044877
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=15
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000001263044856
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1263044830, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1263044867, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1263044877, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1263044856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(428b7730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428b7730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4407): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4407): ====startRecUseTime====
D/htc.customization.log.level( 4407):  is 
W/CustomizationLogLevel( 4407): Level value is invalid, use default level 2
D/CustomizationManager( 4407):  Read ACC file spent 0.120 (s)
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4407): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4407): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4407): Parsing tag category name = system
I/CustomizationCIDLoader( 4407): Parsing tag category name = application
I/CustomizationCIDLoader( 4407): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4407): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4407): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4407): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4407): Parsing tag category name = Settings
D/CustomizationManager( 4407):  Read CID file spent 0.184 (s)
D/CustomizationManager( 4407):  All configurations done spent 0.184 (s)
W/HtcNativeFlag( 4407): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4407): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4407): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4407): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4407, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{422a5c68 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1593): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1593): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1885): Unregistering com.test.thalitest
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/acms    ( 1885): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1455): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(4294fc78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PMS     (  906): releaseWL(4294fc78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PackageBroadcastService( 1223): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4423 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): Delaying start of: ServiceRecord{427435c0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1327): Unsupported attribute readOnly
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4423): install
I/MultiDex( 4423): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4423): loading existing secondary dex files
I/MultiDex( 4423): load found 1 secondary dex files
I/MultiDex( 4423): install done
I/PeopleContactsSync( 1223): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1223, uid=10028, userID:0
D/PMS     (  906): acquireWL(425054b8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
I/Icing   ( 1223): doRemovePackageData com.test.thalitest
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1223): Writing status failed
D/PMS     (  906): releaseWL(425054b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4443 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4423): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4443): install
E/SQLiteDatabase( 1223): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1223): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1223): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1223): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1223): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1223): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1223): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1223): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1223): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1223): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1223): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1223): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4443): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/ClearPendingStateOp( 1223): Runtime exception while performing operation
E/ClearPendingStateOp( 1223): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1223): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1223): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1223): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1223): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1223): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1223): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1223): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1223): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1223): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1223): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4443): loading existing secondary dex files
I/MultiDex( 4443): load found 1 secondary dex files
I/MultiDex( 4443): install done
F/ClearPendingStateOp( 1223): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1223): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1223): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1223): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1223): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1223): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1223): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1223): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1223): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1223): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1223): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1223): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ProviderInstaller( 4443): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/DropBoxManagerService(  906): Can't write: system_app_wtf
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop135.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1399): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SharedPreferencesImpl( 1209): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/SQLiteLog( 1399): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1399): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca77010
W/[PluginManager]RegisterService( 1399): provider may killed!
W/[PluginManager]RegisterService( 1399): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1399): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1399): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1399): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1399): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1399): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1399): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1399): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1399): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1399): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1399): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1399): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1399): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1399): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1399): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2884): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/SQLiteDatabase( 4423): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4423): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4423): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4423): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4423): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4423): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4423): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4423): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4423): threadid=12: thread exiting with uncaught exception (group=0x41727e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
W/SQLiteConnectionPool( 1223): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 1223): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 1223): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
E/AndroidRuntime( 4423): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4423): Process: com.google.android.gms.drive, PID: 4423
E/AndroidRuntime( 4423): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4423): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4423): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4423): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4423): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4423): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4423): 	at ctn.run(SourceFile:985)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4423): killProcess, pid=4423
D/Process ( 4423): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2884): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2884): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63c2df78
W/dalvikvm( 2884): threadid=14: thread exiting with uncaught exception (group=0x41727e30)
E/AndroidRuntime( 2884): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2884): Process: com.google.android.googlequicksearchbox:search, PID: 2884
E/AndroidRuntime( 2884): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2884): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2884): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2884): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2884): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2884): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2884): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2884): 	at cid.d(PG:186)
E/AndroidRuntime( 2884): 	at clo.g(PG:594)
E/AndroidRuntime( 2884): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2884): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2884): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2884): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2884): 	at clr.tL(PG:827)
E/AndroidRuntime( 2884): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2884): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2884): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2884): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2884): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2884): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2884): killProcess, pid=2884
D/Process ( 2884): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2884
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2884): Died!
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2884) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
I/ActivityManager(  906): Recipient 4423
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4423) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10953ms
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/.GelStubAppWatcher: pid=4465 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=522 entropy=516
D/wpa_supplicant( 1161): Add randomness: count=523 entropy=517
D/wpa_supplicant( 1161): Add randomness: count=524 entropy=518
D/wpa_supplicant( 1161): Add randomness: count=525 entropy=519
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=526 entropy=520
D/wpa_supplicant( 1161): Add randomness: count=527 entropy=521
D/wpa_supplicant( 1161): Add randomness: count=528 entropy=522
D/wpa_supplicant( 1161): Add randomness: count=529 entropy=523
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (490) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000001263044830
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000001281212663
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-72
I/wpa_supplicant( 1161): tsf=0000001281212672
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=15
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000001281212646
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1263044830, distance: ?(cm), distanceSd: ?(cm)
I/IcingCorporaProvider( 4465): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1281212663, distance: ?(cm), distanceSd: ?(cm)
E/SQLiteDatabase( 1223): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 1223): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1223): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1223): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1223): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 1223): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 1223): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 1223): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 1223): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 1223): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 1223): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 1223): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 1223): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 1223): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 1223): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1223): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 1223): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 1223): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1223): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1223): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1223): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 1223): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 1223): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 1223): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 1223): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 1223): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 1223): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 1223): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 1223): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 1223): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 1223): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1223): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 1223): Opened games_3a3529a.db in read-only mode
D/WifiP2pService(  906): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 1281212672, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1281212646, distance: ?(cm), distanceSd: ?(cm)
W/dalvikvm( 1223): threadid=10: thread exiting with uncaught exception (group=0x41727e30)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
D/WifiStateMachine(  906): add 4 to mScanResults
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4480 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 1223): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 1223): Process: com.google.android.gms, PID: 1223
E/AndroidRuntime( 1223): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 1223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 1223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1223): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 1223): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 1223): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1223): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 1223): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 1223): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 1223): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 1223): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 1223): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 1223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1223): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1223): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  906): Process com.google.android.gms has crashed too many times: killing!
V/ScoreHelper(  906): Only print Top 10 in ApScanList
D/Process (  906): killProcessQuiet, pid=1223
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Killing 1223:com.google.android.gms/u0a28 (adj 6): crash
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
I/ActivityManager(  906): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4496 uid=10031 gids={50031, 3003, 5012}
D/LocationManagerService(  906): getProviders()=[passive]
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
D/Process (  906): killProcessQuiet, pid=4145
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  906): Killing 4145:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  906): Recipient 4145
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.google.android.gms for service com.google.android.gms/.icing.service.IndexService: pid=4514 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4514): install
I/MultiDex( 4514): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4514): loading existing secondary dex files
I/MultiDex( 4514): load found 1 secondary dex files
I/MultiDex( 4514): install done
I/ProviderInstaller( 4514): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
W/PackageManager(  906): Unable to load service info ResolveInfo{4276c8e8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
