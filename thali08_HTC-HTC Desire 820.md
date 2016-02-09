#### Test 58741471ee11130_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
,I/SensorManager(  903): mEventCount = 600
D/CustomizationManager( 4235): ====startRecUseTime====
D/htc.customization.log.level( 4235):  is 
W/CustomizationLogLevel( 4235): Level value is invalid, use default level 2
D/CustomizationManager( 4235):  Read ACC file spent 0.072 (s)
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4235): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4235): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4235): Parsing tag category name = system
I/CustomizationCIDLoader( 4235): Parsing tag category name = application
I/CustomizationCIDLoader( 4235): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4235): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4235): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4235): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4235): Parsing tag category name = Settings
D/CustomizationManager( 4235):  Read CID file spent 0.121 (s)
D/CustomizationManager( 4235):  All configurations done spent 0.121 (s)
W/HtcNativeFlag( 4235): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4235): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4235): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4235): Fail to get flag for type 'language', use default value: -1
E/cutils-trace( 4235): Error opening trace file: No such file or directory (2)
--------- beginning of /dev/log/system
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4235
,D/PMS     (  903): acquireWL(42638540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  903): n_update end
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42638540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,V/AlarmManager(  903): sending alarm PendingIntent{42729ee8: PendingIntentRecord{420e7378 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=71894, Int=0
,I/CalendarProvider2( 1520): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1520): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(41bf5fc0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3842 10154 null
,I/ActivityManager(  903): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3842): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3842): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3842, uid=10154, userID:0
,D/PMS     (  903): releaseWL(41bf5fc0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 3842): Conditions not met for autocaching.
,I/MusicLeanback( 3842): Stop autocaching.
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4252 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4252): Loading default preferences
,W/Resources( 4252): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  903): New client listening to asynchronous messages
,D/SyncApplication( 4252): Overriding preferences with custom values
,D/SyncApplication( 4252): Updating preferences succeeded
,E/SyncApplication( 4252): Application created.
D/VolumeInfo( 4252): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4252): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4252): Found 0 mount point(s)
,V/VolumeInfo( 4252): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4252): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4252): getNewCalendarAuthority()...
,D/VolumeInfo( 4252): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4252): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4252): enableAppOperation()+
,D/SyncApplication( 4252): enableAppOperation()-
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4252, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4252, uid=10008, userID:0
,W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 4252): isNeorSinged() + 
,D/HTCUtilities( 4252): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4252): isNeorSinged() return false
,D/CDMountReceiver( 4252): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4252): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/CDMountReceiver( 4252): enable CD Auto-mount: true
,D/HTCUtilities( 4252): enable auto-mount
,D/HTCUtilities( 4252): enable auto-mount
,I/ActivityManager(  903): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b9cb38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 2 15 5 11
D/MountService(  903): mountISO: /system/etc/PCTOOL.ISO
,I/ActivityManager(  903): Resuming delayed broadcast
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c37360 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  903): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 2 10 3 16
,W/MediaManager( 3824): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3004
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3004:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3004
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4276 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=43 rxSum=31} preTxRxSum={txSum=37 rxSum=24}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19197 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19198 delay=15s
D/PMS     (  903): releaseWL(4257e9e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/CalendarApplication( 4276): onCreate
D/ProviderChangeReceiver( 4276): ---------------------------------------------------
D/ProviderChangeReceiver( 4276): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 4276): start to updateAlertNotification!
D/Process (  903): killProcessQuiet, pid=3861
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4291 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Killing 3861:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/AlertService( 4276): No fired or scheduled alerts
D/HtcAlertUtils( 4276): -- cancelReminderNotification --
D/HtcAlertUtils( 4276): broadcastExistReminder!
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  903): Recipient 3861
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true,
,V/Settings:HtcSettingsApplication( 4291): [4291/4291] onCreate()
W/ContextImpl( 4291): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3891
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3891:com.htc.sdm/u0a80 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3891
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 9 times.
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{426ae868 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL,
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1155): Change stage from stage0 to stage3
,I/wpa_supplicant( 1155): Don't scan again before 3 minutes, avoid too many scan when stage change frequently
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:74, mTXpacketCount:74, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  903): releaseWL(42534f88): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  903): mEventCount = 750
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 10 times.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): acquireWL(42537998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
,V/AlarmManager(  903): sending alarm PendingIntent{423ae668: PendingIntentRecord{423ac3d0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455023189082, Int=0
,D/PMS     (  903): releaseWL(42537998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4129): [1] 5.onFinished: Installation state replication succeeded.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 11 times.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1415): service - has update message, not stop
,D/AutoSetting( 1415): service - mHandler: update timezone
,I/SensorManager(  903): mEventCount = 900
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1520): service - onCreate()
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1520): service - mHandler: update timezone
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1520): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1520): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c41d28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 8 3 11
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=44 rxSum=32} preTxRxSum={txSum=43 rxSum=31}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19198 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19199 delay=15s
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
D/PMS     (  903): acquireWL(42616a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{425e76d8: PendingIntentRecord{420e7378 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=87669, Int=0
D/PMS     (  903): releaseWL(42616a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 12 times.
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:77, mTXpacketCount:74, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SensorManager(  903): mEventCount = 1050
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1520): Don't start project servcice
,D/HtcModeClient( 1520): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1520): connectState: CONNECTION_READY = false
D/SilentMusic( 1520): call stop
,D/HtcModeClient( 1520): close connection
,W/HtcModeClient( 1520): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1520): read the terminate packet, so break
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  903): mEventCount = 1200
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{425e5378 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  903): acquireWL(425e00a8): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  903): releaseWL(425e00a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(425c0f98): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  903): releaseWL(425c0f98): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(425be020): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  903): releaseWL(425be020): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(425b7020): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  903): releaseWL(425b7020): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=45 rxSum=33} preTxRxSum={txSum=44 rxSum=32}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19199 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19200 delay=15s
D/PMS     (  903): acquireWL(425b4f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{426090c0: PendingIntentRecord{420e7378 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102674, Int=0
D/PMS     (  903): releaseWL(425b4f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4315 uid=10077 gids={50077}
D/PMS     (  903): acquireWL(42579560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10077}
V/AlarmManager(  903): sending alarm PendingIntent{423c9ea0: PendingIntentRecord{41c256c8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455023211203, Int=60000
,D/PMS     (  903): releaseWL(42579560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4315): SMSBackupAgentService started
,D/SMSBackup( 4315): Checking restore status
,D/SMSBackup( 4315): Restore complete
,D/SMSBackup( 4315): cancelCheckAlarm
,D/SMSBackup( 4315): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  903): killProcessQuiet, pid=3929
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3929:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3929
,D/WifiService(  903): Client connection lost with reason: 4
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  903): mEventCount = 1350
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:77, mTXpacketCount:77, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420a2fd8
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  903): pid=903, uid=1000
,W/SensorService(  903): Active sensors: size = 2
,W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420a2fd8, eanble = 0, strlen(mName) = 59
,W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42347c88
,W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@41d45d30
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  903): mWirelessDisplayManager is null
W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 373ms
W/PnPMgr  (  358): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
D/PMS     (  903): OOBE c monitor 11
I/InputMethodManagerService(  903): Disable input method client, pid=1268
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@427441e8)
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/PMN     (  903): wakingUp
I/WindowManager(  903): No lock screen! windowToken=null
D/PMS     (  903): acquireWL(42595e28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
,D/NfcService( 1252): applyRouting -2
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  903): acquireWL(4262d818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(42595e28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  903): onScreenOn
D/PMS     (  903): releaseWL(4262d818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/MtpService( 2419): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2419): [MTP][onReceive]-
,D/NfcService( 1252): applyRouting - 0
D/NfcService( 1252): applyRouting -2
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19201 delay=15s
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): acquireWL(426e05a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
D/PMS     (  903): releaseWL(426e05a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ClockThread( 1115): stop update clock
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4335 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null,
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:On
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): BG scan when screen On
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): Match BG scan, scan!
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =2
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
D/WifiNative-wlan0(  903):    returned true
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  903): updateScreenOn: false
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4335): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(42610f30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4335 1000 null
,D/SmartSyncUtils( 4335): isEpsOn(), nState = 0
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1815): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1815): onScreenOn: 1455023219247
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1815): onScreenOn: 1455023219247
D/PMS     (  903): releaseWL(42610f30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  903): acquireWL(42612a00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1433 10028 null
D/PMS     (  903): releaseWL(42612a00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42347c88
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42347c88, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@41d45d30
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
D/SmartSyncUtils( 4335): getMobilePolicyEnabled, result = true
I/FeedHostManager( 1268): [onPause]
,I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cb5ed8
I/SocialFeedProvider( 1268): +onPause
,I/SocialFeedProvider( 1268): -onPause
D/PMS     (  903): acquireWL(425d25b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Killing 3967:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=3967
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1415): receiver - intent: android.intent.action.USER_PRESENT
,D/PMS     (  903): releaseWL(425d25b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
,I/ActivityManager(  903): Recipient 3967
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19201 mDataStallAlarmIntent=PendingIntent{425ce920: PendingIntentRecord{420e7378 android broadcastIntent}}
,D/AutoSetting( 1415): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:Off
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1155): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42742830): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
D/TetherSettings( 4190): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4190): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4190): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4190): Cust_ConnectToPC   : spcsc>false
D/        ( 4190): Cust_ConnectToPC   : IPT>true
D/        ( 4190): Cust_ConnectToPC   : Singel_USB>false
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/NetworkPolicy(  903): updateScreenOn: false
W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4190): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4190): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4190): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/ContactMessageStore( 1241): start background delete task...
,I/PSReceiver( 4190): onReceive:android.intent.action.USER_PRESENT
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 4190): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4190):  defaultType:0
,W/ContextImpl( 4335): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4335): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4335): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4335): isEpsOn(), nState = 0
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d45d30
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d45d30, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d45d30, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d45d30
D/WifiService(  903): New client listening to asynchronous messages
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41d3a5d0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41d3a5d0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] getTotalRam: 1873 Mb
D/AutoSetting( 1415): service - mHandler: cancel location update
,D/AutoSetting( 1415): service -           changes count: 0
D/PMS     (  903): acquireWL(42644ce8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1433 10028 null
,D/PMS     (  903): releaseWL(42644ce8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1815): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1815): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1815): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1815): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1815): onScreenOff
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42742830): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/PMS     (  903): acquireWL(425ef2e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=112152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425ef2e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1155): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1155): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1155): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I,/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1155): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1155): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1155): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: DISCONNECTED -> INACTIVE
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4264b420 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4264b420 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4264b420 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000114121774
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
,I/wpa_supplicant( 1155): tsf=0000000114121813
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-79
I/wpa_supplicant( 1155): tsf=0000000114121824
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos,
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000114121798
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 114121774, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 114121813, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 114121824, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 114121798, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=4008
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1520): service - handleMessage() quit looper
I/ActivityManager(  903): Killing 4008:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4008
,D/Process (  903): killProcessQuiet, pid=3876
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3876:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3876
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(426a2dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end,
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(426a2dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1155): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1155): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1155): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1155): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1155): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1155): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES",
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000132374768
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55,
I/wpa_supplicant( 1155): tsf=0000000132374805
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000132374815
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
,I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000132374794
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiP2pService(  903): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 132374768, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 132374805, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 132374815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 132374794, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  903): acquireWL(42667040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4240b588: PendingIntentRecord{421f1f78 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140681, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{425cfde0: PendingIntentRecord{4237f3b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141543, Int=0
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(42669140): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  903): releaseWL(42667040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  903): acquireWL(42693be0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e394 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/AutoSetting( 1415): service - handleMessage() stop self
D/PMS     (  903): releaseWL(42693be0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  903): acquireWL(426f8378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426f8378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 34
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/AutoSetting( 1415): service - onDestroy() END
,D/AutoSetting( 1415): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=3540
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3540:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3540
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): releaseWL(42669140): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1155): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1155): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1155): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1155): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplican,t( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1155): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1155): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1155): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1155): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (636) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000150445043
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g,
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000150445080
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000150445090
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000150445070
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90,
I/wpa_supplicant( 1155): tsf=0000000150445099
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 150445043, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 150445080, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 150445090, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 150445070, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 150445099, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 5 to mScanResults
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (5) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1155): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1155): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1155): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1155): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1155): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1155): Add randomness: count=39 entropy=33
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1155): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1155): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (636) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000168771216
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000168771254
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000168771264
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
,I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-53
I/wpa_supplicant( 1155): tsf=0000000168771243
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000168771273
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 168771216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 168771254, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 168771264, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 168771243, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 168771273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 5 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList,
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (5) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(427cbaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=172152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(427cbaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(427cdc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{425fc198: PendingIntentRecord{42487358 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174799, Int=0
,D/PMS     (  903): releaseWL(427cdc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1155): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1155): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1155): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1155): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1155): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1155): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1155): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1155): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (636) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000187014805
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000187014844
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
,I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000187014854
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-53
I/wpa_supplicant( 1155): tsf=0000000187014833
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000187014863
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 187014805, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 187014844, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 187014854, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 187014833, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 187014863, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 5 to mScanResults,
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (5) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(427ec110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(427ec110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1155): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1155): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1155): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1155): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1155): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supp,licant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1155): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1155): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1155): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1155): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1155): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1155): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (902) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000205304857
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000205304893
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000205304903
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-53
I/wpa_supplicant( 1155): tsf=0000000205304883
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000187014863
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000205304912
I/wpa_supplicant( 1155): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000205304923
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 205304857, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 205304893, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 205304903, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 205304883, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachi,ne(  903): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 187014863, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 205304912, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 205304923, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): add 7 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (7) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1155): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1155): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1155): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1155): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1,155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1155): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1155): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1155): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1155): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (755) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000223342118
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000223342144
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
,I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000223342156
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-53
I/wpa_supplicant( 1155): tsf=0000000205304883
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000223342164
I/wpa_supplicant( 1155): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
,I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000223342175
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 223342118, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 223342144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 223342156, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 205304883, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 223342164, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 223342175, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,D/WifiStateMachine(  903): add 6 to mScanResults,
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==,
D/WifiStateMachine(  903): == (6) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4282d9c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=232152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4282d9c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1155): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1155): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1155): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1155): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1155): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1,155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1155): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1155): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1155): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1155): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1155): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (642) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000241554747
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
,I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000241554774
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000241554785
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000241554794
I/wpa_supplicant( 1155): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000241554804
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 241554747, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 241554774, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 241554785, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 241554794, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 241554804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 5 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (5) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(4284af28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4284af28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1155): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1155): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1155): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1155): Add randomness: count=89 entropy=83
D/Wi,fiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (642) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000259814787
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000259814814
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700,
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000259814825
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000241554794
I/wpa_supplicant( 1155): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-91
I/wpa_supplicant( 1155): tsf=0000000241554804
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 259814787, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 259814814, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 259814825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 241554794, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 241554804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 5 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  71, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (5) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1155): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1155): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1155): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1155): Add randomness: count=95 entropy=89
D/wp,a_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000278170175
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000278170202
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2,
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-70
I/wpa_supplicant( 1155): tsf=0000000278170213
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 278170175, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 278170202, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2412, timestamp: 278170213, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4287bf18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000},
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=292152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4287bf18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1155): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1155): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1155): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1155): Add randomness: count=101 entropy=95
D/,WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000296394969
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000296394996
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000296395007
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 296394969, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 296394996, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 296395007, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults,
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1,
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42892570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42892570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available,
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1155): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1155): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
,W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=105 entropy=99
,D/wpa_supplicant( 1155): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1155): Add randomness: count=107 entropy=101
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
,W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000314615047
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000314615072
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000314615083
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 314615047, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 314615072, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 314615083, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42637f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/HtcPowerSaver(  903): updateBatteryInfo
,D/PMS     (  903): releaseWL(42637f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available,
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=108 entropy=102,
D/wpa_supplicant( 1155): Add randomness: count=109 entropy=103
D/wpa_supplicant( 1155): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=111 entropy=105
D/wpa_supplicant( 1155): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1155): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000332864680
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000332864706
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
,I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000332864717
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 332864680, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 332864706, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 332864717, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1155): Add randomness: count=115 entropy=109
D/wpa_supplicant( 1155): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=117 entropy=111
D/wpa_supplicant( 1155): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1155): Add randomness: count=119 entro,py=113
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000350841889
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000350841914
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000350841926
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 350841889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 350841914, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 350841926, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(41d421d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=352153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(41d421d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4368 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
D/PMS     (  903): acquireWL(42654fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10047}
,V/AlarmManager(  903): sending alarm PendingIntent{41f04e60: PendingIntentRecord{41ca7a68 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455023327805, Int=10800000
,V/AlarmManager(  903): sending alarm PendingIntent{42664570: PendingIntentRecord{4268d9d8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1455023464879, Int=0
,D/PMS     (  903): releaseWL(42654fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4368/10047)
,W/Uploader( 1225): No account for auth token provided
,D/Process (  903): killProcessQuiet, pid=4056
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4056:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4056
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c13 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299,
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
I/global  ( 1225): call createSocket() return a new socket.
D/libc    ( 1225): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e534c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4129): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4129): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4129): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4129): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4129): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4129): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4129): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4129): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 10 3 12
,D/libc    ( 4129): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4129): [NET] getaddrinfo-,err=8
D/libc    ( 4129): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4129): [NET] getaddrinfo-, 1
,D/libc    ( 4129): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =38c9 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4129): [NET] getaddrinfo_proxy-, success
,I/global  ( 4129): call createSocket() return a new socket.
D/libc    ( 4129): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4129): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4129): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4129): [NET] getaddrinfo-,err=8
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1155): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1155): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
,I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1155): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1155): Add randomness: count=125 entropy=119
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000369025024
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g,
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000369025050
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000369025061
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 369025024, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 369025050, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 369025061, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults,
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4283ad58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4283ad58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1155): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1155): Add randomness: count=128 entropy=122
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1155): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1155): Add randomness: count=131 entro,py=125
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
,I/wpa_supplicant( 1155): tsf=0000000387271812
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000387271837
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000387271849
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 387271812, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 387271837, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 387271849, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults,
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==,
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=132 entropy=126
D/wpa_supplicant( 1155): Add randomness: count=133 entropy=127
D/wpa_supplicant( 1155): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1155): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1155): Add randomness: count=137 entro,py=131
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000405525297
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000405525323
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-73
I/wpa_supplicant( 1155): tsf=0000000405525334
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 405525297, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 405525323, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 405525334, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4264a648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=412153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4264a648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1155): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1155): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1155): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1155): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
,I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000423774855
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000423774882
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000423774893
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 423774855, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 423774882, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 423774893, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42667480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42667480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1155): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1155): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
,D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1155): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1155): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1,
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000442024560
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000442024586
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000442024597
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 442024560, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 442024586, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 442024597, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available,
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
,D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1155): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1155): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=153 entropy=147
D/wpa_supplicant( 1155): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1155): Add randomness: count=155 entropy=149
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa,_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000460341835
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000460341861
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000460341872
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 460341835, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 460341861, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 460341872, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(4279eab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=472152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4279eab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=156 entropy=150
D/wpa_supplicant( 1155): Add randomness: count=157 entropy=151
D/wpa_supplicant( 1155): Add randomness: count=158 entropy=152
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=159 entropy=153
D/wpa_supplicant( 1155): Add randomness: count=160 entropy=154
D/wpa_supplicant( 1155): Add randomness: count=161 entro,py=155
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000460341835
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
,I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000478575351
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000478575364
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 460341835, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 478575351, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 478575364, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4280b6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4280b6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-69
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=162 entropy=156
D/wpa_supplicant( 1155): Add randomness: count=163 entropy=157
D/wpa_supplicant( 1155): Add randomness: count=164 entropy=158
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-69
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=1,65 entropy=159
D/wpa_supplicant( 1155): Add randomness: count=166 entropy=160
D/wpa_supplicant( 1155): Add randomness: count=167 entropy=161
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  903): getDiscoveryDongleList
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000496561915
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000496561942
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-69
I/wpa_supplicant( 1155): tsf=0000000496561953
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 496561915, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 496561942, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -69, frequency: 2412, timestamp: 496561953, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 13 [-69], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==,
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-69
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=168 entropy=162
D/wpa_supplicant( 1155): Add randomness: count=169 entropy=163
D/wpa_supplicant( 1155): Add randomness: count=170 entropy=164
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-69
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=171 entropy=165
D/wpa_supplicant( 1155): Add randomness: count=172 entropy=166
D/wpa_supplicant( 1155): Add randomness: count=173 entro,py=167
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000514908757
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000514908783
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-69
I/wpa_supplicant( 1155): tsf=0000000514908794
,I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 514908757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 514908783, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -69, frequency: 2412, timestamp: 514908794, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults,
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 13 [-69], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(4281f3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=532152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4281f3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=174 entropy=168
D/wpa_supplicant( 1155): Add randomness: count=175 entropy=169
D/wpa_supplicant( 1155): Add randomness: count=176 entropy=170
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-71
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=1,77 entropy=171
D/wpa_supplicant( 1155): Add randomness: count=178 entropy=172
D/wpa_supplicant( 1155): Add randomness: count=179 entropy=173
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000533181781
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412,
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000533181808
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-71
I/wpa_supplicant( 1155): tsf=0000000533181819
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 533181781, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 533181808, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2412, timestamp: 533181819, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults,
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(420aae88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(420aae88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=180 entropy=174
D/wpa_supplicant( 1155): Add randomness: count=181 entropy=175
D/wpa_supplicant( 1155): Add randomness: count=182 entropy=176
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=183 entropy=177
D/wpa_supplicant( 1155): Add randomness: count=184 entropy=178
D/wpa_supplicant( 1155): Add randomness: count=185 entro,py=179
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000551426040
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000551426066
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000551426077
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####,
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 551426040, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 551426066, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 551426077, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=186 entropy=180
D/wpa_supplicant( 1155): Add randomness: count=187 entropy=181
D/wpa_supplicant( 1155): Add randomness: count=188 entropy=182
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-72
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=189 entropy=183
D/wpa_supplicant( 1155): Add randomness: count=190 entropy=184
D/wpa_supplicant( 1155): Add randomness: count=191 entro,py=185
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000569762040
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000569762066
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-72
I/wpa_supplicant( 1155): tsf=0000000569762077
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 569762040, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 569762066, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2412, timestamp: 569762077, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000),
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available,
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing,
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=192 entropy=186
,D/wpa_supplicant( 1155): Add randomness: count=193 entropy=187
D/wpa_supplicant( 1155): Add randomness: count=194 entropy=188
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
,D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=195 entropy=189
D/wpa_supplicant( 1155): Add randomness: count=196 entropy=190
D/wpa_supplicant( 1155): Add randomness: count=197 entropy=191
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000588042084
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000588042109
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-73
I/wpa_supplicant( 1155): tsf=0000000588042120
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  903): Only print Top 10 in ApScanList
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 588042084, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 588042109, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 588042120, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000),
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/PMS     (  903): acquireWL(42685cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000},
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=592152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42685cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=198 entropy=192
D/wpa_supplicant( 1155): Add randomness: count=199 entropy=193
D/wpa_supplicant( 1155): Add randomness: count=200 entropy=194
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=201 entropy=195
D/wpa_supplicant( 1155): Add randomness: count=202 entropy=196
D/wpa_supplicant( 1155): Add randomness: count=203 entro,py=197
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000606241867
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000606241892
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-73
I/wpa_supplicant( 1155): tsf=0000000606241903
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 606241867, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 606241892, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 606241903, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(426efbe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426efbe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=204 entropy=198
D/wpa_supplicant( 1155): Add randomness: count=205 entropy=199
D/wpa_supplicant( 1155): Add randomness: count=206 entropy=200
D/wpa_supplicant( 1155): Add randomness: count=207 entropy=201
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=208 entropy=202
D/wpa_supplicant( 1155): Add randomness: count=209 entropy=203
D/wpa_supplicant( 1155): Add randomness: count=210 entropy=204
D/wpa_supplicant( 1155): Add randomness: count=211 entropy=205
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000606241867
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000624485087
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-73
I/wpa_supplicant( 1155): tsf=0000000624485097
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000624485075
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 606241867, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 624485087, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 624485097, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 624485075, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==,
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter,
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=212 entropy=206
D/wpa_supplicant( 1155): Add randomness: count=213 entropy=207
D/wpa_supplicant( 1155): Add randomness: count=214 entropy=208
D/wpa_supplicant( 1155): Add randomness: count=215 entropy=209
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=216 entropy=210
D/wpa_supplicant( 1155): Add randomness: count=217 entropy=211
D/wpa_supplicant( 1155): Add randomness: count=218 entropy=212
D/wpa_supplicant( 1155): Add randomness: count=219 entropy=213
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000642822005
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000642822042
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000642822052
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000642822030
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 642822005, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 642822042, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 642822052, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 642822030, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==,
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42844538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=652153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42844538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=220 entropy=214
D/wpa_supplicant( 1155): Add randomness: count=221 entropy=215
D/wpa_supplicant( 1155): Add randomness: count=222 entropy=216
D/wpa_supplicant( 1155): Add randomness: count=223 entropy=217
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=224 entropy=218
D/wpa_supplicant( 1155): Add randomness: count=225 entropy=219
D/wpa_supplicant( 1155): Add randomness: count=226 entropy=220
D/wpa_supplicant( 1155): Add randomness: count=227 entropy=221
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000661054546
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000661054583
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412,
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000661054593
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000661054572
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 661054546, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 661054583, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 661054593, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 661054572, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList,
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/Process (  903): killProcessQuiet, pid=3954
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3954:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3954
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42822ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42822ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=228 entropy=222
D/wpa_supplicant( 1155): Add randomness: count=229 entropy=223
D/wpa_supplicant( 1155): Add randomness: count=230 entropy=224
D/wpa_supplicant( 1155): Add randomness: count=231 entropy=225
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=232 entropy=226
D/wpa_supplicant( 1155): Add randomness: count=233 entropy=227
D/wpa_supplicant( 1155): Add randomness: count=234 entropy=228
D/wpa_supplicant( 1155): Add randomness: count=235 entropy=229
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000679304782
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
,I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000679304819
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000000679304829
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000679304808
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 679304782, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 679304819, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 679304829, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 679304808, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=236 entropy=230
D/wpa_supplicant( 1155): Add randomness: count=237 entropy=231
D/wpa_supplicant( 1155): Add randomness: count=238 entropy=232
D/wpa_supplicant( 1155): Add randomness: count=239 entropy=233
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=240 entropy=234
D/wpa_supplicant( 1155): Add randomness: count=241 entropy=235
D/wpa_supplicant( 1155): Add randomness: count=242 entropy=236
D/wpa_supplicant( 1155): Add randomness: count=243 entropy=237
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000697671124
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000697671161
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-73
I/wpa_supplicant( 1155): tsf=0000000697671171
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000697671150
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 697671124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 697671161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 697671171, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 697671150, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(428c1570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=712152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(428c1570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=244 entropy=238
D/wpa_supplicant( 1155): Add randomness: count=245 entropy=239
D/wpa_supplicant( 1155): Add randomness: count=246 entropy=240
D/wpa_supplicant( 1155): Add randomness: count=247 entropy=241
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=248 entropy=242
D/wpa_supplicant( 1155): Add randomness: count=249 entropy=243
D/wpa_supplicant( 1155): Add randomness: count=250 entropy=244
D/wpa_supplicant( 1155): Add randomness: count=251 entropy=245
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000715924943
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1,
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000715924980
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-85
I/wpa_supplicant( 1155): tsf=0000000715924991
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
,I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000715924969
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 715924943, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 715924980, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 715924991, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 715924969, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(428dadd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(428dadd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=252 entropy=246
D/wpa_supplicant( 1155): Add randomness: count=253 entropy=247
D/wpa_supplicant( 1155): Add randomness: count=254 entropy=248
D/wpa_supplicant( 1155): Add randomness: count=255 entropy=249
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplican,t( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=256 entropy=250
D/wpa_supplicant( 1155): Add randomness: count=257 entropy=251
D/wpa_supplicant( 1155): Add randomness: count=258 entropy=252
D/wpa_supplicant( 1155): Add randomness: count=259 entropy=253
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000715924943
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000733962194
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000733962204
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000733962184
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 715924943, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 733962194, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 733962204, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 733962184, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList,
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(428f9278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428f9278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=260 entropy=254
D/wpa_supplicant( 1155): Add randomness: count=261 entropy=255
D/wpa_supplicant( 1155): Add randomness: count=262 entropy=256
D/wpa_supplicant( 1155): Add randomness: count=263 entropy=257
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
,I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1155): Add randomness: count=264 entropy=258
D/wpa_supplicant( 1155): Add randomness: count=265 entropy=259
D/wpa_supplicant( 1155): Add randomness: count=266 entropy=260
D/wpa_supplicant( 1155): Add randomness: count=267 entropy=261
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47,
I/wpa_supplicant( 1155): tsf=0000000752194863
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000752194899
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000752194909
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000752194889
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 752194863, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 752194899, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 752194909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 752194889, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available,
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
,I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0,
D/wpa_supplicant( 1155): Add randomness: count=268 entropy=262
D/wpa_supplicant( 1155): Add randomness: count=269 entropy=263
D/wpa_supplicant( 1155): Add randomness: count=270 entropy=264
D/wpa_supplicant( 1155): Add randomness: count=271 entropy=265
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411,
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=272 entropy=266
D/wpa_supplicant( 1155): Add randomness: count=273 entropy=267
D/wpa_supplicant( 1155): Add randomness: count=274 entropy=268
D/wpa_supplicant( 1155): Add randomness: count=275 entropy=269
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000770531963
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000770531999
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
,I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000770532009
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000770531989
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 770531963, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 770531999, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 770532009, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 770531989, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4292f698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=772152, Int=0
,D/PMS     (  903): releaseWL(4292f698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available,
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47,
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=276 entropy=270
D/wpa_supplicant( 1155): Add randomness: count=277 entropy=271
D/wpa_supplicant( 1155): Add randomness: count=278 entropy=272
D/wpa_supplicant( 1155): Add randomness: count=279 entropy=273,
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
,I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1155): Add randomness: count=280 entropy=274
D/wpa_supplicant( 1155): Add randomness: count=281 entropy=275
D/wpa_supplicant( 1155): Add randomness: count=282 entropy=276
D/wpa_supplicant( 1155): Add randomness: count=283 entropy=277
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found,
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000788784814
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000788784851
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-85
I/wpa_supplicant( 1155): tsf=0000000788784863
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
,I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000788784840
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 788784814, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 788784851, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 788784863, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 788784840, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4293c0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(4293c0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=284 entropy=278
D/wpa_supplicant( 1155): Add randomness: count=285 entropy=279
D/wpa_supplicant( 1155): Add randomness: count=286 entropy=280
D/wpa_supplicant( 1155): Add randomness: count=287 entropy=281
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=288 entropy=282
D/wpa_supplicant( 1155): Add randomness: count=289 entropy=283
D/wpa_supplicant( 1155): Add randomness: count=290 entropy=284
D/wpa_supplicant( 1155): Add randomness: count=291 entropy=285
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000806881854
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
,I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000806881892
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-77
I/wpa_supplicant( 1155): tsf=0000000806881902
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55,
I/wpa_supplicant( 1155): tsf=0000000806881880
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 806881854, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 806881892, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 806881902, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 806881880, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==,
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=292 entropy=286
D/wpa_supplicant( 1155): Add randomness: count=293 entropy=287
D/wpa_supplicant( 1155): Add randomness: count=294 entropy=288
D/wpa_supplicant( 1155): Add randomness: count=295 entropy=289
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
,D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
,I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1155): Add randomness: count=296 entropy=290
D/wpa_supplicant( 1155): Add randomness: count=297 entropy=291
D/wpa_supplicant( 1155): Add randomness: count=298 entropy=292
D/wpa_supplicant( 1155): Add randomness: count=299 entropy=293
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000825210901
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
,I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000825210937
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000825210947
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====,
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000825210926
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 825210901, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 825210937, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 825210947, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 825210926, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==,
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(424e7490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=832153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(424e7490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=300 entropy=294
D/wpa_supplicant( 1155): Add randomness: count=301 entropy=295
D/wpa_supplicant( 1155): Add randomness: count=302 entropy=296
D/wpa_supplicant( 1155): Add randomness: count=303 entropy=297
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=304 entropy=298
D/wpa_supplicant( 1155): Add randomness: count=305 entropy=299
,D/wpa_supplicant( 1155): Add randomness: count=306 entropy=300
D/wpa_supplicant( 1155): Add randomness: count=307 entropy=301
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
,W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1,
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000843474834
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000843474871
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000843474881
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-53
I/wpa_supplicant( 1155): tsf=0000000843474860
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####,
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 843474834, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 843474871, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 843474881, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 843474860, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4263a520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4263a520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available,
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
,I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1155): Add randomness: count=308 entropy=302
D/wpa_supplicant( 1155): Add randomness: count=309 entropy=303
D/wpa_supplicant( 1155): Add randomness: count=310 entropy=304
D/wpa_supplicant( 1155): Add randomness: count=311 entropy=305
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
,I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
,I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
,I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=312 entropy=306
D/wpa_supplicant( 1155): Add randomness: count=313 entropy=307
D/wpa_supplicant( 1155): Add randomness: count=314 entropy=308
D/wpa_supplicant( 1155): Add randomness: count=315 entropy=309
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000861734843
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000861734879
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000861734889
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-53,
I/wpa_supplicant( 1155): tsf=0000000861734868
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 861734843, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 861734879, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 861734889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 861734868, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(426e5038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(426e5038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=316 entropy=310
D/wpa_supplicant( 1155): Add randomness: count=317 entropy=311
D/wpa_supplicant( 1155): Add randomness: count=318 entropy=312
D/wpa_supplicant( 1155): Add randomness: count=319 entropy=313
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=320 entropy=314
D/wpa_supplicant( 1155): Add randomness: count=321 entropy=315
D/wpa_supplicant( 1155): Add randomness: count=322 entropy=316
D/wpa_supplicant( 1155): Add randomness: count=323 entropy=317
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000879902227
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000879902263,
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000879902273
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-53
I/wpa_supplicant( 1155): tsf=0000000879902252
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 879902227, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 879902263, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 879902273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 879902252, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(427f7a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=892153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(427f7a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=324 entropy=318
D/wpa_supplicant( 1155): Add randomness: count=325 entropy=319
D/wpa_supplicant( 1155): Add randomness: count=326 entropy=320
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=327 entropy=321
D/wpa_supplicant( 1155): Add randomness: count=328 entropy=322
D/wpa_supplicant( 1155): Add randomness: count=329 entro,py=323
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000897911824
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55,
I/wpa_supplicant( 1155): tsf=0000000897911850
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-81
I/wpa_supplicant( 1155): tsf=0000000897911862
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=7,
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-53
I/wpa_supplicant( 1155): tsf=0000000879902252
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 897911824, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 897911850, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 897911862, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 879902252, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-53], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4270d6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4270d6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=330 entropy=324
D/wpa_supplicant( 1155): Add randomness: count=331 entropy=325
D/wpa_supplicant( 1155): Add randomness: count=332 entropy=326
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=333 entropy=327
D/wpa_supplicant( 1155): Add randomness: count=334 entropy=328
D/wpa_supplicant( 1155): Add randomness: count=335 entro,py=329
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000915942036
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000915942061
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700,
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-82
I/wpa_supplicant( 1155): tsf=0000000915942073
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 915942036, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 915942061, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 915942073, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42631f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42631f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available,
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=336 entropy=330
D/wpa_supplicant( 1155): Add randomness: count=337 entropy=331
D/wpa_supplicant( 1155): Add randomness: count=338 entropy=332
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1,
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55,
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters,
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
,I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=339 entropy=333
D/wpa_supplicant( 1155): Add randomness: count=340 entropy=334
D/wpa_supplicant( 1155): Add randomness: count=341 entropy=335
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000934184895
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000934184923
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-82
I/wpa_supplicant( 1155): tsf=0000000934184934
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 934184895, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 934184923, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 934184934, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(4291e4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=952153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4291e4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=342 entropy=336
D/wpa_supplicant( 1155): Add randomness: count=343 entropy=337
D/wpa_supplicant( 1155): Add randomness: count=344 entropy=338
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=345 entropy=339
D/wpa_supplicant( 1155): Add randomness: count=346 entropy=340
D/wpa_supplicant( 1155): Add randomness: count=347 entro,py=341
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000952490371
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000952490399
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-80
I/wpa_supplicant( 1155): tsf=0000000952490410
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList,
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 952490371, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 952490399, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 952490410, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WirelessDisplayService(  903): getDiscoveryDongleList
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=348 entropy=342
D/wpa_supplicant( 1155): Add randomness: count=349 entropy=343
D/wpa_supplicant( 1155): Add randomness: count=350 entropy=344
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=3,51 entropy=345
D/wpa_supplicant( 1155): Add randomness: count=352 entropy=346
D/wpa_supplicant( 1155): Add randomness: count=353 entropy=347
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000970761817
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
,I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000970761844
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000970761855
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000),
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 970761817, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 970761844, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 970761855, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList,
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(425d4e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(425d4e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4266fda0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4266fda0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=354 entropy=348
D/wpa_supplicant( 1155): Add randomness: count=355 entropy=349
D/wpa_supplicant( 1155): Add randomness: count=356 entropy=350
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=357 entropy=351
D/wpa_supplicant( 1155): Add randomness: count=358 entropy=352
D/wpa_supplicant( 1155): Add randomness: count=359 entro,py=353
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000000988921639
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000000988921657
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000000988921665
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 988921639, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 988921657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 988921665, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=360 entropy=354
D/wpa_supplicant( 1155): Add randomness: count=361 entropy=355
D/wpa_supplicant( 1155): Add randomness: count=362 entropy=356
D/wpa_supplicant( 1155): Add randomness: count=363 entropy=357
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=364 entropy=358
D/wpa_supplicant( 1155): Add randomness: count=365 entropy=359
D/wpa_supplicant( 1155): Add randomness: count=366 entropy=360
D/wpa_supplicant( 1155): Add randomness: count=367 entropy=361
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001007289356
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001007289393
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-75
I/wpa_supplicant( 1155): tsf=0000001007289403
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000001007289382
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1007289356, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1007289393, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 1007289403, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1007289382, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList,
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4270eb08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  903): sending alarm PendingIntent{41d52f60: PendingIntentRecord{42433f20 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784671, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{41d60400: PendingIntentRecord{42413e80 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=927652, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{41d47558: PendingIntentRecord{41d47500 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455024048151, Int=900000
D/PMS     (  903): acquireWL(427d2520): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1368 10028 null
,V/AlarmManager(  903): sending alarm PendingIntent{424ab300: PendingIntentRecord{426e73c8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455024119353, Int=0
,D/PMS     (  903): releaseWL(427d2520): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): acquireWL(42714548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,W/ContextImpl( 4335): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(42714548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4335): call getInstance()
,D/SmartSyncUtils( 4335): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4335): MY_DEBUG = false
D/PMS     (  903): acquireWL(42883570): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4335 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4335): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4335): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4335): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4335): SettingOnTime = 1455084000000, randomSettingOnTime = 1455081161000
D/SmartSyncScreenOnOffTimeReceiver( 4335): SettingOffTime = 1455062400000, randomSettingOffTime = 1455068097000
,D/SmartSyncScreenOnOffTimeReceiver( 4335): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 4335): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4335): bNightModeTurnOffOnce = false
D/PMS     (  903): releaseWL(4270eb08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  903): releaseWL(42883570): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  903): Couldn't get kernel wake lock stats
,I/dalvikvm-heap(  903): Grow heap (frag case) to 17.814MB for 149604-byte allocation
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(4280fce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1012152, Int=0
,D/PMS     (  903): releaseWL(4280fce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42441188): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
,D/GCM     ( 1368): Message class mow
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1368/10028)
,D/PMS     (  903): releaseWL(42441188): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(41c9d6a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  903): releaseWL(41c9d6a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=368 entropy=362
D/wpa_supplicant( 1155): Add randomness: count=369 entropy=363
D/wpa_supplicant( 1155): Add randomness: count=370 entropy=364
D/wpa_supplicant( 1155): Add randomness: count=371 entropy=365
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=372 entropy=366
D/wpa_supplicant( 1155): Add randomness: count=373 entropy=367
D/wpa_supplicant( 1155): Add randomness: count=374 entropy=368
D/wpa_supplicant( 1155): Add randomness: count=375 entropy=369
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001025524710
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001025524746
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000001025524756
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000001025524735
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1025524710, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1025524746, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1025524756, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1025524735, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(426290c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426290c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=376 entropy=370
D/wpa_supplicant( 1155): Add randomness: count=377 entropy=371
D/wpa_supplicant( 1155): Add randomness: count=378 entropy=372
D/wpa_supplicant( 1155): Add randomness: count=379 entropy=373
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_sup,plicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=380 entropy=374
D/wpa_supplicant( 1155): Add randomness: count=381 entropy=375
D/wpa_supplicant( 1155): Add randomness: count=382 entropy=376
D/wpa_supplicant( 1155): Add randomness: count=383 entropy=377
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001043754820
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001043754857
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
,I/wpa_supplicant( 1155): tsf=0000001043754867
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000001043754847
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1043754820, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1043754857, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1043754867, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1043754847, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=384 entropy=378
D/wpa_supplicant( 1155): Add randomness: count=385 entropy=379
D/wpa_supplicant( 1155): Add randomness: count=386 entropy=380
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=387 entropy=381
D/wpa_supplicant( 1155): Add randomness: count=388 entropy=382
D/wpa_supplicant( 1155): Add randomness: count=389 entro,py=383
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001062110749
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001062110775,
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000001062110787
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=8
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-54
I/wpa_supplicant( 1155): tsf=0000001043754847
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1062110749, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1062110775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1062110787, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 1043754847, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 4 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-54], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/PMS     (  903): acquireWL(425dff18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1072153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425dff18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=390 entropy=384
D/wpa_supplicant( 1155): Add randomness: count=391 entropy=385
D/wpa_supplicant( 1155): Add randomness: count=392 entropy=386
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=393 entropy=387
D/wpa_supplicant( 1155): Add randomness: count=394 entropy=388
D/wpa_supplicant( 1155): Add randomness: count=395 entro,py=389
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001080355056
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001080355083
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-74
I/wpa_supplicant( 1155): tsf=0000001080355094
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1080355056, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  903): Only print Top 10 in ApScanList
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1080355083, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 1080355094, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults,
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42664038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42664038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=396 entropy=390
D/wpa_supplicant( 1155): Add randomness: count=397 entropy=391
D/wpa_supplicant( 1155): Add randomness: count=398 entropy=392
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=399 entropy=393
D/wpa_supplicant( 1155): Add randomness: count=400 entropy=394
D/wpa_supplicant( 1155): Add randomness: count=401 entro,py=395
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001098594748
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001098594774
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-70
I/wpa_supplicant( 1155): tsf=0000001098594785
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1098594748, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1098594774, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2412, timestamp: 1098594785, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/PMS     (  903): acquireWL(427113e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(427113e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-44
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=402 entropy=396
D/wpa_supplicant( 1155): Add randomness: count=403 entropy=397
D/wpa_supplicant( 1155): Add randomness: count=404 entropy=398
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-44
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=405 entropy=399
D/wpa_supplicant( 1155): Add randomness: count=406 entropy=400
D/wpa_supplicant( 1155): Add randomness: count=407 entropy=401
,D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-44
I/wpa_supplicant( 1155): tsf=0000001116854753
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g,
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001116854779
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-70
I/wpa_supplicant( 1155): tsf=0000001116854790
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -44, frequency: 5220, timestamp: 1116854753, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1116854779, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2412, timestamp: 1116854790, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-44], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(42801b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1132153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42801b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=408 entropy=402
D/wpa_supplicant( 1155): Add randomness: count=409 entropy=403
D/wpa_supplicant( 1155): Add randomness: count=410 entropy=404
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=411 entropy=405
D/wpa_supplicant( 1155): Add randomness: count=412 entropy=406
D/wpa_supplicant( 1155): Add randomness: count=413 entro,py=407
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-46
I/wpa_supplicant( 1155): tsf=0000001135160228
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
,I/wpa_supplicant( 1155): tsf=0000001135160254
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-70
I/wpa_supplicant( 1155): tsf=0000001135160266
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  903): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1135160228, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1135160254, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2412, timestamp: 1135160266, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(42869da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(42869da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1155): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=414 entropy=408
D/wpa_supplicant( 1155): Add randomness: count=415 entropy=409
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/wpa_supplicant( 1155): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=416 entropy=410
D/wpa_supplicant( 1155): Add randomness: count=417 entropy=411
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA ,subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-46
I/wpa_supplicant( 1155): tsf=0000001135160228
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001153374614
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-70
I/wpa_supplicant( 1155): tsf=0000001135160266
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1135160228, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1153374614, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2412, timestamp: 1135160266, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=418 entropy=412
D/wpa_supplicant( 1155): Add randomness: count=419 entropy=413
D/wpa_supplicant( 1155): Add randomness: count=420 entropy=414
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=421 entropy=415
D/wpa_supplicant( 1155): Add randomness: count=422 entropy=416
D/wpa_supplicant( 1155): Add randomness: count=423 entro,py=417
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
,I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001171681440
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001171681467
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000001171681478
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1171681440, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1171681467, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1171681478, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=424 entropy=418
D/wpa_supplicant( 1155): Add randomness: count=425 entropy=419
D/wpa_supplicant( 1155): Add randomness: count=426 entropy=420
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=427 entropy=421
D/wpa_supplicant( 1155): Add randomness: count=428 entropy=422
D/wpa_supplicant( 1155): Add randomness: count=429 entro,py=423
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001189972128
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001189972154
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000001189972166
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1189972128, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1189972154, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1189972166, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(427ebb58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1192152, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(427ebb58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=430 entropy=424
D/wpa_supplicant( 1155): Add randomness: count=431 entropy=425
D/wpa_supplicant( 1155): Add randomness: count=432 entropy=426
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=433 entropy=427
D/wpa_supplicant( 1155): Add randomness: count=434 entropy=428
D/wpa_supplicant( 1155): Add randomness: count=435 entro,py=429
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001208181927
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001208181954
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000001208181965
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1208181927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1208181954, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1208181965, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(427ef630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(427ef630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  903): acquireWL(427f0ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(427f0ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=436 entropy=430
D/wpa_supplicant( 1155): Add randomness: count=437 entropy=431
D/wpa_supplicant( 1155): Add randomness: count=438 entropy=432
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=439 entropy=433
D/wpa_supplicant( 1155): Add randomness: count=440 entropy=434
D/wpa_supplicant( 1155): Add randomness: count=441 entro,py=435
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001226395104
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001226395130
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000001226395142
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1226395104, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1226395130, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1226395142, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=442 entropy=436
D/wpa_supplicant( 1155): Add randomness: count=443 entropy=437
D/wpa_supplicant( 1155): Add randomness: count=444 entropy=438
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=445 entropy=439
D/wpa_supplicant( 1155): Add randomness: count=446 entropy=440
D/wpa_supplicant( 1155): Add randomness: count=447 entro,py=441
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0,
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001244731968
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001244731994
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000001244732006
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
,I/wpa_supplicant( 1155): ####
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1244731968, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1244731994, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1244732006, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42835918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4234ea08: PendingIntentRecord{41f27730 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1252153, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42835918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=448 entropy=442
D/wpa_supplicant( 1155): Add randomness: count=449 entropy=443
D/wpa_supplicant( 1155): Add randomness: count=450 entropy=444
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=451 entropy=445
D/wpa_supplicant( 1155): Add randomness: count=452 entropy=446
D/wpa_supplicant( 1155): Add randomness: count=453 entro,py=447
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (376) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001263004196
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001263004223
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000001263004234
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1263004196, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1263004223, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1263004234, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  903): add 3 to mScanResults
,V/ScoreHelper(  903): Only print Top 10 in ApScanList
,V/ScoreHelper(  903):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
,D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (3) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42686ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(42686ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
,D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,TIME-OUT KILL (timeout was 1200000ms),D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=454 entropy=448
D/wpa_supplicant( 1155): Add randomness: count=455 entropy=449
D/wpa_supplicant( 1155): Add randomness: count=456 entropy=450
D/wpa_supplicant( 1155): Add randomness: count=457 entropy=451
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 9
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 0
I/wpa_supplicant( 1155): wpa_s->is_screen_on 0
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1155): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1155): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1155): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1155): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1155): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=458 entropy=452
D/wpa_supplicant( 1155): Add randomness: count=459 entropy=453
D/wpa_supplicant( 1155): Add randomness: count=460 entropy=454
D/wpa_supplicant( 1155): Add randomness: count=461 entropy=455
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): clear disabled list - type=1
I/wpa_supplicant( 1155): No suitable network found
W/wpa_supplicant( 1155): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1155): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1155): reply (489) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-47
I/wpa_supplicant( 1155): tsf=0000001281262752
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001281262784
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000001281262794
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=Gonzos
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=9
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-55
I/wpa_supplicant( 1155): tsf=0000001281262772
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 1281262752, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 1281262784, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1281262794, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1281262772, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  903):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (4) end of scan result ==
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
E/cutils-trace( 4408): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4408): ====startRecUseTime====
D/htc.customization.log.level( 4408):  is 
W/CustomizationLogLevel( 4408): Level value is invalid, use default level 2
D/CustomizationManager( 4408):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4408): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4408): Parsing tag category name = system
I/CustomizationCIDLoader( 4408): Parsing tag category name = application
I/CustomizationCIDLoader( 4408): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4408): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4408): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4408): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4408): Parsing tag category name = Settings
D/CustomizationManager( 4408):  Read CID file spent 0.156 (s)
D/CustomizationManager( 4408):  All configurations done spent 0.156 (s)
W/HtcNativeFlag( 4408): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4408): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4408): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4408): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4408, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  903): Skipping PackageSetting{42024188 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
W/PackageManager(  903): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  903): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
I/acms    ( 1863): Unregistering com.test.thalitest
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1433): Ignoring removeGeofence because network location is disabled.
E/acms    ( 1863): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  903): acquireWL(42946f70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1433 10028 null
D/PMS     (  903): releaseWL(42946f70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
D/VoicemailCleanupService( 1295): Cleaning up data for package: com.test.thalitest
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PackageBroadcastService( 1225): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4422 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
F/PackageManager(  903): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  903): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager(  903): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager(  903): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager(  903): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  903): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  903): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  903): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  903): 	at com.android.internal.util.FastXmlSerializer.escapeAndAppendString(FastXmlSerializer.java:145)
F/PackageManager(  903): 	at com.android.internal.util.FastXmlSerializer.attribute(FastXmlSerializer.java:176)
F/PackageManager(  903): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1203)
F/PackageManager(  903): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  903): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  903): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  903): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  903): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  903): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  903): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager(  903): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  903): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager(  903): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager(  903): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager(  903): 	... 14 more
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
I/PackageManager(  903): Failed to clean up mangled file: /data/system/packages-stopped.xml
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1455024390508.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  903): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  903): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  903): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  903): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  903): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  903): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  903): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  903): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  903): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  903): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  903): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 18 more
I/ActivityManager(  903): Delaying start of: ServiceRecord{426e0778 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4422): install
I/PeopleContactsSync( 1225): CP2 sync disabled
I/MultiDex( 4422): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1225, uid=10028, userID:0
D/PMS     (  903): acquireWL(425e5c68): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
I/Icing   ( 1225): doRemovePackageData com.test.thalitest
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1225): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1225): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1225): Writing status failed
I/MultiDex( 4422): loading existing secondary dex files
I/MultiDex( 4422): load found 1 secondary dex files
D/PMS     (  903): releaseWL(425e5c68): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4422): install done
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4442 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4422): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/MultiDex( 4442): install
I/MultiDex( 4442): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4442): loading existing secondary dex files
I/MultiDex( 4442): load found 1 secondary dex files
I/MultiDex( 4442): install done
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4442): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/SQLiteDatabase( 1225): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1225): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1225): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1225): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1225): Runtime exception while performing operation
E/ClearPendingStateOp( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1225): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1225): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1225): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1225): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1225): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1225): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1225): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  903): Resuming delayed broadcast
E/SharedPreferencesImpl( 1205): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/DropBoxManagerService(  903): Can't write: system_app_wtf
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
I/[PluginManager]RegisterService( 1415): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SQLiteLog( 1415): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1415): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca19948
W/[PluginManager]RegisterService( 1415): provider may killed!
W/[PluginManager]RegisterService( 1415): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1415): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1415): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1415): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1415): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1415): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1415): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1415): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1415): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1415): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1415): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/SQLiteDatabase( 4422): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4422): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4422): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4422): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4422): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4422): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4422): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4422): 	at ctn.run(SourceFile:985)
I/IcingCorporaProvider( 2866): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/dalvikvm( 4422): threadid=12: thread exiting with uncaught exception (group=0x416c9e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4422): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4422): Process: com.google.android.gms.drive, PID: 4422
E/AndroidRuntime( 4422): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4422): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4422): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4422): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4422): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4422): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4422): 	at ctn.run(SourceFile:985)
D/Process ( 4422): killProcess, pid=4422
D/Process ( 4422): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
E/SQLiteLog( 2866): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2866): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63ad1070
W/dalvikvm( 2866): threadid=14: thread exiting with uncaught exception (group=0x416c9e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  903): Recipient 4422
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4422) has died.
E/AndroidRuntime( 2866): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2866): Process: com.google.android.googlequicksearchbox:search, PID: 2866
E/AndroidRuntime( 2866): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2866): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2866): 	at cid.d(PG:186)
E/AndroidRuntime( 2866): 	at clo.g(PG:594)
E/AndroidRuntime( 2866): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2866): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2866): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2866): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2866): 	at clr.tL(PG:827)
E/AndroidRuntime( 2866): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2866): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2866): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2866): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2866): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  903): Resuming delayed broadcast
D/Process ( 2866): killProcess, pid=2866
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4465 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
D/Process ( 2866): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
W/PackageManager(  903): Unable to load service info ResolveInfo{4270c040 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 1225): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1225): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 1225): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 1225): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 1225): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 1225): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 1225): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 1225): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 1225): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 1225): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 1225): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 1225): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 1225): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1225): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1225): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 1225): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1225): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 1225): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 1225): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 1225): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 1225): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 1225): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 1225): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 1225): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 1225): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 1225): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 1225): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 1225): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1225): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1225): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 1225): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 1225): threadid=10: thread exiting with uncaught exception (group=0x416c9e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1225): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 1225): Process: com.google.android.gms, PID: 1225
E/AndroidRuntime( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1225): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 1225): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 1225): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 1225): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 1225): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 1225): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1225): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  903): Process com.google.android.gms has crashed too many times: killing!
D/Process (  903): killProcessQuiet, pid=1225
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
I/ActivityManager(  903): Killing 1225:com.google.android.gms/u0a28 (adj 6): crash
D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2866): Died!
D/WifiService(  903): Client connection lost with reason: 4
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2866
I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2866) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
E/SQLiteDatabase( 4465): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4465): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4465): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4465): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4465): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4465): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4465): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4465): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4465): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4465): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4465): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4465): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4465): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4465): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4465): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4465): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4465): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4465): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4465): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4465): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4465): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4465): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4465): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4465): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4465): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4465): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4465): 	at com.android.internal.os.Zygo,teInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4465): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4465): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4465): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4465): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4465): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4465): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4465): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4465): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4465): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4465): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4465): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4465): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4465): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4465): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4465): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4465): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4465): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4465): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4465): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4465): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4465): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4465): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4465): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4465): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4465): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4465): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4465): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4465): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4465): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4465): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4465): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4465): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4465): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4465): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4465): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4465): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4465): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4465): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4465): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4465): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4465): 	at aho.run(AbstractDatabaseInstance.java:455)

```
