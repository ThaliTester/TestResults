#### Test 586024278176cca_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 26
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 52
D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  901):    returned true
,E/cutils-trace( 4128): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4128): ====startRecUseTime====
D/htc.customization.log.level( 4128):  is 
W/CustomizationLogLevel( 4128): Level value is invalid, use default level 2
D/CustomizationManager( 4128):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4128): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4128): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4128): Parsing tag category name = system
I/CustomizationCIDLoader( 4128): Parsing tag category name = application
I/CustomizationCIDLoader( 4128): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4128): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4128): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4128): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4128): Parsing tag category name = Settings
D/CustomizationManager( 4128):  Read CID file spent 0.110 (s)
D/CustomizationManager( 4128):  All configurations done spent 0.110 (s)
W/HtcNativeFlag( 4128): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4128): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4128): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4128): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4128
,I/HtcModeClient( 1497): handler message = 4011
E/HtcModeClient( 1497): Check connection and retry 8 times.
I/SensorManager(  901): mEventCount = 600
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 91
D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,I/CalendarProvider2( 1497): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1497): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  901): Resuming delayed broadcast
,I/ActivityManager(  901): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  901): Resuming delayed broadcast
,D/PMS     (  901): acquireWL(425c1d30): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3821 10154 null
,I/ActivityManager(  901): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3821): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3821): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3821, uid=10154, userID:0
,I/MusicLeanback( 3821): Conditions not met for autocaching.
,I/MusicLeanback( 3821): Stop autocaching.
D/PMS     (  901): releaseWL(425c1d30): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  901): Resuming delayed broadcast
,I/ActivityManager(  901): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4145 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4145): Loading default preferences
,W/Resources( 4145): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/PMS     (  901): acquireWL(42342670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  901): releaseWL(42342670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,D/WifiService(  901): New client listening to asynchronous messages
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,D/SyncApplication( 4145): Overriding preferences with custom values
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/SyncApplication( 4145): Updating preferences succeeded
,E/SyncApplication( 4145): Application created.
D/VolumeInfo( 4145): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4145): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
,V/VolumeInfo( 4145): Found 0 mount point(s)
,V/VolumeInfo( 4145): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4145): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4145): getNewCalendarAuthority()...
,D/VolumeInfo( 4145): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4145): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4145): enableAppOperation()+
,D/SyncApplication( 4145): enableAppOperation()-
,D/HTCUtilities( 4145): isNeorSinged() + 
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4145, uid=10008, userID:0
W/PackageManager(  901): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4145, uid=10008, userID:0
W/PackageManager(  901): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4145): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4145): isNeorSinged() return false
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{427d60b8 u0 com.htc.musicenhancer/.EnhancerService}
,D/CDMountReceiver( 4145): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4145): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4145): enable CD Auto-mount: true
I/RemoteViews( 1113): com.nero.android.htc.sync (false,0)
,D/HTCUtilities( 4145): enable auto-mount
,D/PMS     (  901): releaseWL(4248d9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/HTCUtilities( 4145): enable auto-mount
I/ActivityManager(  901): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/MountService(  901): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  901): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41b43a68 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  901): Resuming delayed broadcast
,I/RemoteViews.Performance( 1113): com.nero.android.htc.sync 2 15 3 11
I/RemoteViews( 1113): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41b82cb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  901): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4168 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/RemoteViews.Performance( 1113): com.nero.android.htc.sync 0 11 4 16
,D/CalendarApplication( 4168): onCreate
D/ProviderChangeReceiver( 4168): ---------------------------------------------------
,D/ProviderChangeReceiver( 4168): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4168): start to updateAlertNotification!
,D/Process (  901): killProcessQuiet, pid=3711
I/ActivityManager(  901): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4182 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  901): Killing 3711:com.htc.sense.news/u0a75 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AlertService( 4168): No fired or scheduled alerts
,D/HtcAlertUtils( 4168): -- cancelReminderNotification --
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcAlertUtils( 4168): broadcastExistReminder!
,I/ActivityManager(  901): Recipient 3711
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4182): [4182/4182] onCreate()
W/ContextImpl( 4182): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  901): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  901): Resuming delayed broadcast
,D/Process (  901): killProcessQuiet, pid=3840,
,I/ActivityManager(  901): Killing 3840:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  901): Recipient 3840
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/MediaManager( 3802): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  901): killProcessQuiet, pid=3874
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 3874:com.htc.sdm/u0a80 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 3874
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  901): releaseWL(42660c00): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 130
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 9 times.
,D/WifiDataStallTracker(  901): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  901): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  901): updateDataStallInfo: mDataStallTxRxSum={txSum=149 rxSum=146} preTxRxSum={txSum=149 rxSum=146}
D/WifiDataStallTracker(  901): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  901): onDataStallAlarm: tag=20313 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  901): startDataStallAlarm: tag=20314 delay=15s
D/PMS     (  901): acquireWL(426c39e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
V/AlarmManager(  901): sending alarm PendingIntent{42614980: PendingIntentRecord{41e6e970 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=74975, Int=0
D/PMS     (  901): releaseWL(426c39e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(4268fe38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10073}
,V/AlarmManager(  901): sending alarm PendingIntent{42648478: PendingIntentRecord{4265d990 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454935006142, Int=0
,D/PMS     (  901): releaseWL(4268fe38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3932): [1] 5.onFinished: Installation state replication succeeded.
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 169
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): [ScoreAP] + current TXpacket:184, mTXpacketCount:184, avgLinkspeed:33,mAvgTxRate54
,D/WifiStateMachine(  901): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 10 times.
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 39
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1392): service - has update message, not stop
,D/AutoSetting( 1392): service - mHandler: update timezone
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  901): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  901): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1497): service - onCreate()
,D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1497): service - mHandler: update timezone
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1497): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1497): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41ba3620 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 1 6 1 11
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 78
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 11 times.
,I/SensorManager(  901): mEventCount = 750
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 117
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 189
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 12 times.
,D/WifiDataStallTracker(  901): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  901): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  901): updateDataStallInfo: mDataStallTxRxSum={txSum=150 rxSum=147} preTxRxSum={txSum=149 rxSum=146}
D/WifiDataStallTracker(  901): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  901): onDataStallAlarm: tag=20314 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  901): startDataStallAlarm: tag=20315 delay=15s
D/PMS     (  901): acquireWL(42561a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
V/AlarmManager(  901): sending alarm PendingIntent{4254c8e8: PendingIntentRecord{41e6e970 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=89982, Int=0
D/PMS     (  901): releaseWL(42561a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  901): acquireWL(4255a818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=90465, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4255a818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1113): now=1454935020058 next=59942
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 228
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): [ScoreAP] + current TXpacket:187, mTXpacketCount:184, avgLinkspeed:45,mAvgTxRate54
,D/WifiStateMachine(  901): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1497): handler message = 4011
,E/HtcModeClient( 1497): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1497): Don't start project servcice
,D/HtcModeClient( 1497): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1497): connectState: CONNECTION_READY = false
,D/SilentMusic( 1497): call stop
,D/HtcModeClient( 1497): close connection
,W/HtcModeClient( 1497): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1497): read the terminate packet, so break
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 39
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{42347ab8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 78
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 117
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/PMS     (  901): acquireWL(424faf80): PARTIAL_WAKE_LOCK  Icing 0x1 1221 10028 null
,D/PMS     (  901): releaseWL(424faf80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  901): acquireWL(424ccae0): PARTIAL_WAKE_LOCK  Icing 0x1 1221 10028 null
,D/PMS     (  901): releaseWL(424ccae0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  901): acquireWL(4249fa30): PARTIAL_WAKE_LOCK  Icing 0x1 1221 10028 null
,D/PMS     (  901): releaseWL(4249fa30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  901): acquireWL(42497ef0): PARTIAL_WAKE_LOCK  Icing 0x1 1221 10028 null
,D/PMS     (  901): releaseWL(42497ef0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  901): acquireWL(4248d9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4248d9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  901): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4207 uid=10077 gids={50077}
,D/PMS     (  901): acquireWL(423d9ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10077}
V/AlarmManager(  901): sending alarm PendingIntent{42379ab8: PendingIntentRecord{42617048 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454935033222, Int=60000
,D/PMS     (  901): releaseWL(423d9ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4207): SMSBackupAgentService started
,D/SMSBackup( 4207): Checking restore status
,D/SMSBackup( 4207): Restore complete
,D/SMSBackup( 4207): cancelCheckAlarm
,D/SMSBackup( 4207): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  901): killProcessQuiet, pid=3903
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 3903:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 3903
D/WifiService(  901): Client connection lost with reason: 4
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 156
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/WifiDataStallTracker(  901): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  901): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  901): updateDataStallInfo: mDataStallTxRxSum={txSum=151 rxSum=148} preTxRxSum={txSum=150 rxSum=147}
D/WifiDataStallTracker(  901): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  901): onDataStallAlarm: tag=20315 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  901): startDataStallAlarm: tag=20316 delay=15s
D/PMS     (  901): acquireWL(42584538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
V/AlarmManager(  901): sending alarm PendingIntent{426623b8: PendingIntentRecord{41e6e970 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104989, Int=0
D/PMS     (  901): releaseWL(42584538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 195
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): [ScoreAP] + current TXpacket:188, mTXpacketCount:187, avgLinkspeed:39,mAvgTxRate54
,D/WifiStateMachine(  901): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  901): Going to sleep due to screen timeout...
,I/SensorManager(  901): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421c3758
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  901): disable: get sensor name = CM36282 Light sensor
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 2
W/SensorService(  901): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421c3758, eanble = 0, strlen(mName) = 59
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  901): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4205ca20
W/SensorService(  901): Listener[1] = com.htc.smartdim.sensor_eye@4258d318
,W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  901): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  901): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  901): mWirelessDisplayManager is null
W/BatSI   (  901): Couldn't get kernel wake lock stats
V/LightsService(  901): setLight #2: color=#0
D/qdlights(  901): set_light_buttons_func: on=0 brightness=0
V/LightsService(  901): setLight #0: color=#0
,D/SurfaceControl(  901): Excessive delay in blankDisplay() while turning screen off: 399ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  901): nativeSetInteractive:false
D/PMS     (  901): nativeSetInteractive:false done
D/PMS     (  901): nativeSetAutoSuspend:true
D/PMS     (  901): nativeSetAutoSuspend:true done
D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0
,D/NfcService( 1252): applyRouting -2
D/HABCtrl (  901): TPE algorithm. remove timeout.
D/PMS     (  901): OOBE c monitor 11
I/InputManager(  901): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  901): screenObserver, isScreenOn=false
I/InputMethodManagerService(  901): Disable input method client, pid=1266
,D/PMS     (  901): acquireWL(42653768): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  901): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4264b8a8)
,V/KeyguardServiceDelegate(  901): **** SHOWN CALLED ****
D/WirelessDisplayService(  901): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  901): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  901): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  901): wakingUp
D/PMS     (  901): releaseWL(42653768): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/WindowManager(  901): No lock screen! windowToken=null
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/WifiDataStallTracker(  901): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  901): startDataStallAlarm: tag=20317 delay=15s
D/PMN     (  901): onScreenOn
D/AlarmManager(  901): ACTION_SCREEN_ON
I/AlarmManager(  901): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  901): [AlarmQueuing] done recovering
I/AlarmManager(  901): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  901): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2706): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2706): [MTP][onReceive]-
D/NfcService( 1252): applyRouting - 0
,D/NfcService( 1252): applyRouting -2
D/PMS     (  901): acquireWL(4265e338): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/PMS     (  901): releaseWL(4265e338): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  901): batLight: Full, plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c800
D/qdlights(  901): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  901): [LedInfo] has indicator attribute
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  901): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  901): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  901): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  901): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): SET_SCREEN_ON:On
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1178): BG scan when screen On
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): Match BG scan, scan!
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  901):    returned true
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/ClockThread( 1113): stop update clock
,I/ActivityManager(  901): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4229 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/NotificationService(  901): batLight: Full, plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c800
D/qdlights(  901): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  901): [LedInfo] has indicator attribute
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  901): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  901): updateScreenOn: false
,W/ContextImpl( 4229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1811): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): onScreenOn: 1454935039773
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1811): onScreenOn: 1454935039773
D/PMS     (  901): acquireWL(427c28c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1468 10028 null
D/PMS     (  901): releaseWL(427c28c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  901): acquireWL(427dfb30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4229 1000 null
D/SmartSyncUtils( 4229): isEpsOn(), nState = 0
,I/SensorManager(  901): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4205ca20
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  901): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 2
W/SensorService(  901): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4205ca20, eanble = 0, strlen(mName) = 91
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  901): Listener[0] = com.htc.smartdim.sensor_eye@4258d318
,W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  901): goingToSleep
I/FeedHostManager( 1266): [onPause]
,I/FeedProviderManager( 1266): onPause
,I/FeedHostManager( 1266): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42304180
I/SocialFeedProvider( 1266): +onPause
,I/SocialFeedProvider( 1266): -onPause
D/PMS     (  901): acquireWL(426e5990): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 901 1000 null
D/PMS     (  901): releaseWL(427dfb30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/WifiDataStallTracker(  901): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  901): stopDataStallAlarm: current tag=20317 mDataStallAlarmIntent=PendingIntent{427f79a8: PendingIntentRecord{41e6e970 android broadcastIntent}}
D/AlarmManager(  901): ACTION_SCREEN_OFF
I/AlarmManager(  901): [AlarmQueuing] screen off now: 
I/AlarmManager(  901): [AlarmQueuing] data connection: true
I/AlarmManager(  901): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  901): doBoolean: SET_SCREEN_ON 0
D/PMS     (  901): acquireWL(42750378): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 901 1000 null
D/PMS     (  901): releaseWL(426e5990): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 4229): getMobilePolicyEnabled, result = true
,I/ActivityManager(  901): Killing 3955:com.htc.task.gtask/u0a67 (adj 15): empty #17
D/Process (  901): killProcessQuiet, pid=3955
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  901): Recipient 3955
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): SET_SCREEN_ON:Off
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1178): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 39
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 39
,D/WifiNative-wlan0(  901):    returned true
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1392): receiver - intent: android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  901): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3755): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/AutoSetting( 1392): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/        ( 3755): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3755): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3755): Cust_ConnectToPC   : spcsc>false
D/        ( 3755): Cust_ConnectToPC   : IPT>true
D/        ( 3755): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3755): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3755): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3755): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3755): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,I/PSReceiver( 3755): onReceive:android.intent.action.USER_PRESENT
D/NetworkPolicy(  901): updateScreenOn: false
,W/ContextImpl( 3755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3755): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3755): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3755):  defaultType:0
,W/ContextImpl( 4229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4229): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4229): getMobilePolicyEnabled, result = true
,I/PhoneStatusBar( 1113): removeHeadsNotification.gc: 57
,D/SmartSyncUtils( 4229): isEpsOn(), nState = 0
,D/WifiService(  901): New client listening to asynchronous messages
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  901): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4258d318
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  901): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 1
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4258d318, eanble = 0, strlen(mName) = 36
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  901): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 0
W/SensorService(  901): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4258d318, eanble = 0, strlen(mName) = 36
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  901): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4258d318
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
E/ActivityThread(  901): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4236c9e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  901): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4236c9e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  901): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  901): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  901): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  901): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  901): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  901): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  901): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  901): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  901): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  901): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  901): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  901): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  901): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  901): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  901): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  901): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  901): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  901): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  901): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
D/AutoSetting( 1392): service - mHandler: cancel location update
D/AutoSetting( 1392): service -           changes count: 0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1811): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1811): onScreenOff
D/PMS     (  901): acquireWL(427b3920): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1468 10028 null
D/PMS     (  901): releaseWL(427b3920): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0],
D/PMS     (  901): releaseWL(42750378): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1178): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1178): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1178): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_s,upplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1178): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1178): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1178): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000112455967
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000112456006
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000112456016
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000112455994
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@427ced08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@427ced08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@427ced08 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 112455967, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 112456006, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 112456016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 112455994, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList,
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
D/Process (  901): killProcessQuiet, pid=4002
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4002:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4002
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  901): killProcessQuiet, pid=3855
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 3855:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 3855
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32,
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1178): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1178): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1178): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available,
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
,I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1178): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1178): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1178): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/WirelessDisplayService(  901): getDiscoveryDongleList
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
,I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000129855366
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000129855404,
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000129855414
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000129855393
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 129855366, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 129855404, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 129855414, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 129855393, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(427154d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(427154d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/AutoSetting( 1392): service - handleMessage() stop self
,D/AutoSetting( 1392): service - onDestroy() END
,D/AutoSetting( 1392): service - handleMessage() quit looper
D/Process (  901): killProcessQuiet, pid=3523
,I/ActivityManager(  901): Killing 3523:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  901): Recipient 3523
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  901): acquireWL(42719bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10028}
,V/AlarmManager(  901): sending alarm PendingIntent{41d77338: PendingIntentRecord{425c40b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141030, Int=0
,V/AlarmManager(  901): sending alarm PendingIntent{42037828: PendingIntentRecord{4250eb60 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141814, Int=0
,D/GpsLocationProvider(  901): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  901): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  901): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  901): acquireWL(42730fd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 901 1000 null
D/PMS     (  901): releaseWL(42719bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  901): acquireWL(42732660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  901): releaseWL(42732660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  901): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  901): [NET] getaddrinfo-,err=8
D/libc    (  901): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  901): [NET] getaddrinfo-, 1
,D/libc    (  901): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6742 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  901): [NET] getaddrinfo_proxy-, success
I/global  (  901): call createSocket() return a new socket.
D/libc    (  901): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  901): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  901): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  901): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  901):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  901): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  901): releaseWL(42730fd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1178): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1178): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1178): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1178): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1178): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1178): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000147234784
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000147234822
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000147234832
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000147234811
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 147234784, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 147234822, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 147234832, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 147234811, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  901): acquireWL(42843a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=150466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42843a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1178): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1178): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1178): Add randomness: count=33 entropy=27
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1178): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1178): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1178): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000164655148
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000164655185
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000164655195
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000164655174
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 164655148, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 164655185, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 164655195, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 164655174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
,D/PMS     (  901): acquireWL(42769290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10026}
,V/AlarmManager(  901): sending alarm PendingIntent{423671b0: PendingIntentRecord{42692028 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173238, Int=0
,D/PMS     (  901): releaseWL(42769290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1178): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1178): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1178): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1178): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1178): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1178): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000182075190
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000182075227
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000182075237
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000182075216
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 182075190, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 182075227, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 182075237, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 182075216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42782a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42782a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46,
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1178): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1178): Add randomness: count=48 entropy=42
,D/wpa_supplicant( 1178): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
,I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
,I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1178): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1178): Add randomness: count=52 entropy=46
,D/wpa_supplicant( 1178): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987,
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000182075190
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000199505195
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000199505205
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000199505182
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 182075190, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 199505195, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 199505205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 199505182, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4279b8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=210465, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4279b8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1178): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1178): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1178): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1178): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1178): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1178): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000216945080
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000216945117
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000216945128
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000216945106
,I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 216945080, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 216945117, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 216945128, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 216945106, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults,
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=62 entropy=56
D/wpa_supplicant( 1178): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1178): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-70
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1178): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1178): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000234342011
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1,
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000234342037
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-70
I/wpa_supplicant( 1178): tsf=0000000234342048
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000216945106
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  901): InactiveState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 234342011, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 234342037, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2412, timestamp: 234342048, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 216945106, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(428686f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d43d40: PendingIntentRecord{424d7438 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=234469, Int=0
,I/ActivityManager(  901): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4256 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  901): sending alarm PendingIntent{424e96a8: PendingIntentRecord{424dbd18 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454935141967, Int=10800000
,D/PMS     (  901): acquireWL(4286b780): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): releaseWL(428686f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(4286d770): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(4286b780): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(4286d770): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.aurora (4256/10047)
,D/Process (  901): killProcessQuiet, pid=2737
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 2737:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  901): Recipient 2737
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1178): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1178): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1178): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1178): Add randomness: count=73 entropy=67
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1178): ,WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000251786462
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000251786488
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-81
I/wpa_supplicant( 1178): tsf=0000000251786499
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 251786462, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 251786488, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 251786499, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42890120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42890120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1178): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1178): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1178): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1178): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000269204984
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000269205009
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-84
I/wpa_supplicant( 1178): tsf=0000000269205020
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 269204984, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 269205009, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 269205020, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(428a5e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=270466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(428a5e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1178): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1178): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1178): Add randomness: count=83 entropy=77
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1178): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1178): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1178): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000286615478
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000286615504
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-75
I/wpa_supplicant( 1178): tsf=0000000286615525
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000286615514
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 286615478, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 286615504, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 286615525, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 286615514, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1178): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1178): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1178): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1178): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1178): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1178): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000304012292
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000304012316
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-75
I/wpa_supplicant( 1178): tsf=0000000304012338
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000304012327
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 304012292, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 304012316, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 304012338, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 304012327, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
D/WirelessDisplayService(  901): getDiscoveryDongleList
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(428d6cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(428d6cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1178): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1178): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1178): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1178): Add randomness: count=101 entropy=95
D/wpa_supplicant( 1178): Add randomness: count=102 entropy=96
D/wpa_supplicant( 1178): Add randomness: count=103 entropy=97
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000321426113
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000321426141
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000321426162
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000321426152
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 321426113, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 321426141, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 321426162, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 321426152, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(428e2cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=330466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(428e2cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=104 entropy=98
D/wpa_supplicant( 1178): Add randomness: count=105 entropy=99
D/wpa_supplicant( 1178): Add randomness: count=106 entropy=100
D/wpa_supplicant( 1178): Add randomness: count=107 entropy=101
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_us,ed=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=108 entropy=102
D/wpa_supplicant( 1178): Add randomness: count=109 entropy=103
,D/wpa_supplicant( 1178): Add randomness: count=110 entropy=104
D/wpa_supplicant( 1178): Add randomness: count=111 entropy=105
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000338835477
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000338835503
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000338835524
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000338835513
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 338835477, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 338835503, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 338835524, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 338835513, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  901): acquireWL(425e9fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10028}
,V/AlarmManager(  901): sending alarm PendingIntent{42523510: PendingIntentRecord{425234d8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1454935285037, Int=0
,D/PMS     (  901): releaseWL(425e9fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 1221): No account for auth token provided
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e0d2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=112 entropy=106
D/wpa_supplicant( 1178): Add randomness: count=113 entropy=107
D/wpa_supplicant( 1178): Add randomness: count=114 entropy=108
D/wpa_supplicant( 1178): Add randomness: count=115 entropy=109
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=116 entropy=110
D/wpa_supplicant( 1178): Add randomness: count=117 entropy=111
D/wpa_supplicant( 1178): Add randomness: count=118 entropy=112
D/wpa_supplicant( 1178): Add randomness: count=119 entropy=113
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000356204684
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000356204710
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
,I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-83
I/wpa_supplicant( 1178): tsf=0000000356204731
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000356204721
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 356204684, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 356204710, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 356204731, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 356204721, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
I/global  ( 1221): call createSocket() return a new socket.
D/libc    ( 1221): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-, SUCCESS,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1221/10028),
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/PlayEventLogger( 3932): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3932): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3932): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3932): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3932): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
,E/PlayEventLogger( 3932): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3932): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3932): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41eaee98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 1 10 3 12
,D/libc    ( 3932): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3932): [NET] getaddrinfo-,err=8
D/libc    ( 3932): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3932): [NET] getaddrinfo-, 1
,D/libc    ( 3932): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d693 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3932): [NET] getaddrinfo_proxy-, success
,I/global  ( 3932): call createSocket() return a new socket.
D/libc    ( 3932): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 3932): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 3932): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3932): [NET] getaddrinfo-,err=8
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  901): acquireWL(41e437f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(41e437f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=120 entropy=114
D/wpa_supplicant( 1178): Add randomness: count=121 entropy=115
D/wpa_supplicant( 1178): Add randomness: count=122 entropy=116
D/wpa_supplicant( 1178): Add randomness: count=123 entropy=117
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=124 entropy=118
D/wpa_supplicant( 1178): Add randomness: count=125 entropy=119
D/wpa_supplicant( 1178): Add randomness: count=126 entropy=120
D/wpa_supplicant( 1178): Add randomness: count=127 entropy=121
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000373625096
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
,I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000373625122
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-83
I/wpa_supplicant( 1178): tsf=0000000373625143
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos,
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000373625133
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 373625096, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 373625122, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 373625143, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 373625133, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  901): acquireWL(423b9b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=390466, Int=0
,D/PMS     (  901): releaseWL(423b9b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=128 entropy=122
D/wpa_supplicant( 1178): Add randomness: count=129 entropy=123
D/wpa_supplicant( 1178): Add randomness: count=130 entropy=124
D/wpa_supplicant( 1178): Add randomness: count=131 entropy=125
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=132 entropy=126
D/wpa_supplicant( 1178): Add randomness: count=133 entropy=127
D/wpa_supplicant( 1178): Add randomness: count=134 entropy=128
D/wpa_supplicant( 1178): Add randomness: count=135 entropy=129
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000391021026
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000391021063
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-83
,I/wpa_supplicant( 1178): tsf=0000000391021073
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000391021052
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 391021026, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 391021063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 391021073, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 391021052, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=136 entropy=130
D/wpa_supplicant( 1178): Add randomness: count=137 entropy=131
D/wpa_supplicant( 1178): Add randomness: count=138 entropy=132
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=139 entropy=133
D/wpa_supplicant( 1178): Add randomness: count=140 entropy=134
D/wpa_supplicant( 1178): Add randomness: count=141 entropy=135
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000408384967
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000408385004
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-83
I/wpa_supplicant( 1178): tsf=0000000391021073
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4,
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000408384993
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): InactiveState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 408384967, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 408385004, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 391021073, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 408384993, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults,
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter,
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=142 entropy=136
D/wpa_supplicant( 1178): Add randomness: count=143 entropy=137
D/wpa_supplicant( 1178): Add randomness: count=144 entropy=138
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=145 entropy=139
D/wpa_supplicant( 1178): Add randomness: count=146 entropy=140
D/wpa_supplicant( 1178): Add randomness: count=147 entropy=141
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelemen,t id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (351) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000425765174
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
,I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000425765210
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000425765200
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 425765174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 425765210, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
V/ScoreHelper(  901): Only print Top 10 in ApScanList
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 425765200, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (3) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4267c750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4267c750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=148 entropy=142
D/wpa_supplicant( 1178): Add randomness: count=149 entropy=143
D/wpa_supplicant( 1178): Add randomness: count=150 entropy=144
D/wpa_supplicant( 1178): Add randomness: count=151 entropy=145
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=152 entropy=146
D/wpa_supplicant( 1178): Add randomness: count=153 entropy=147
D/wpa_supplicant( 1178): Add randomness: count=154 entropy=148
D/wpa_supplicant( 1178): Add randomness: count=155 entropy=149
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000443185067
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
,I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000443185103
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000443185093
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=5
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000443185113
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 443185067, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000),
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 443185103, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 443185093, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 443185113, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42620050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=450466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42620050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=156 entropy=150
D/wpa_supplicant( 1178): Add randomness: count=157 entropy=151
D/wpa_supplicant( 1178): Add randomness: count=158 entropy=152
D/wpa_supplicant( 1178): Add randomness: count=159 entropy=153
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
,I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1178): Add randomness: count=160 entropy=154
D/wpa_supplicant( 1178): Add randomness: count=161 entropy=155
D/wpa_supplicant( 1178): Add randomness: count=162 entropy=156
D/wpa_supplicant( 1178): Add randomness: count=163 entropy=157
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000460565393
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000460565432
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000460565420
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=5
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000460565442,
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 460565393, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 460565432, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 460565420, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 460565442, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,D/WifiStateMachine(  901): add 4 to mScanResults,
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=164 entropy=158
D/wpa_supplicant( 1178): Add randomness: count=165 entropy=159
D/wpa_supplicant( 1178): Add randomness: count=166 entropy=160
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
,I/wpa_supplicant( 1178): wpa_s->is_screen_on 0,
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=167 entropy=161
D/wpa_supplicant( 1178): Add randomness: count=168 entropy=162
D/wpa_supplicant( 1178): Add randomness: count=169 entropy=163
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/WirelessDisplayService(  901): getDiscoveryDongleList
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000477915082
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000477915109
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000460565420
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=5
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73,
I/wpa_supplicant( 1178): tsf=0000000477915119
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 477915082, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 477915109, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 460565420, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 477915119, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  901): acquireWL(42892058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  901): releaseWL(42892058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
,D/HtcPowerSaver(  901): Checking...
,I/HtcPowerSaver(  901): >> updateStatus
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=170 entropy=164
D/wpa_supplicant( 1178): Add randomness: count=171 entropy=165
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=172 entropy=166
D/wpa_supplicant( 1178): Add randomness: count=173 entropy=167
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wp,a_supplicant( 1178): WPS: WFA subelement id=0 len=1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000494964239
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000494964264
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=5
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000477915119
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 494964239, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 494964264, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 477915119, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  901): acquireWL(4267f800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=510466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4267f800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=174 entropy=168
D/wpa_supplicant( 1178): Add randomness: count=175 entropy=169
D/wpa_supplicant( 1178): Add randomness: count=176 entropy=170
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=177 entropy=171
D/wpa_supplicant( 1178): Add randomness: count=178 entropy=172
D/wpa_supplicant( 1178): Add randomness: count=179 entropy=173
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelemen,t id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (351) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000512361717
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000512361744
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000512361754
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 512361717, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 512361744, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 512361754, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=180 entropy=174
D/wpa_supplicant( 1178): Add randomness: count=181 entropy=175
D/wpa_supplicant( 1178): Add randomness: count=182 entropy=176
D/wpa_supplicant( 1178): Add randomness: count=183 entropy=177
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=184 entropy=178
D/wpa_supplicant( 1178): Add randomness: count=185 entropy=179
D/wpa_supplicant( 1178): Add randomness: count=186 entropy=180
D/wpa_supplicant( 1178): Add randomness: count=187 entropy=181
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000529785063
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
,I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000529785089
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000529785099
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000529785110
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 529785063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 529785089, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 529785099, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 529785110, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=188 entropy=182
D/wpa_supplicant( 1178): Add randomness: count=189 entropy=183
D/wpa_supplicant( 1178): Add randomness: count=190 entropy=184
D/wpa_supplicant( 1178): Add randomness: count=191 entropy=185
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=192 entropy=186
D/wpa_supplicant( 1178): Add randomness: count=193 entropy=187
D/wpa_supplicant( 1178): Add randomness: count=194 entropy=188
D/wpa_supplicant( 1178): Add randomness: count=195 entropy=189
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000547165702
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000547165729
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000547165738,
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000547165749
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 547165702, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 547165729, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 547165738, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 547165749, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(427b0838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(427b0838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter,
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=196 entropy=190
D/wpa_supplicant( 1178): Add randomness: count=197 entropy=191
D/wpa_supplicant( 1178): Add randomness: count=198 entropy=192
D/wpa_supplicant( 1178): Add randomness: count=199 entropy=193
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=200 entropy=194
D/wpa_supplicant( 1178): Add randomness: count=201 entropy=195
D/wpa_supplicant( 1178): Add randomness: count=202 entropy=196
D/wpa_supplicant( 1178): Add randomness: count=203 entropy=197
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000564545209
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000564545245
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000564545235
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000564545255
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 564545209, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 564545245, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 564545235, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 564545255, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(428dac98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=570466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(428dac98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=204 entropy=198
D/wpa_supplicant( 1178): Add randomness: count=205 entropy=199
D/wpa_supplicant( 1178): Add randomness: count=206 entropy=200
D/wpa_supplicant( 1178): Add randomness: count=207 entropy=201
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=208 entropy=202
D/wpa_supplicant( 1178): Add randomness: count=209 entropy=203
D/wpa_supplicant( 1178): Add randomness: count=210 entropy=204
D/wpa_supplicant( 1178): Add randomness: count=211 entropy=205
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000581925186
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000581925223
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000581925213
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000581925233
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 581925186, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 581925223, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 581925213, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 581925233, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42878c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42878c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=212 entropy=206
D/wpa_supplicant( 1178): Add randomness: count=213 entropy=207
D/wpa_supplicant( 1178): Add randomness: count=214 entropy=208
D/wpa_supplicant( 1178): Add randomness: count=215 entropy=209
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=216 entropy=210
D/wpa_supplicant( 1178): Add randomness: count=217 entropy=211
D/wpa_supplicant( 1178): Add randomness: count=218 entropy=212
D/wpa_supplicant( 1178): Add randomness: count=219 entropy=213
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000599315180
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000599315216
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000599315206
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000599315226
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 599315180, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 599315216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 599315206, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 599315226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4287e8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4287e8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=220 entropy=214
D/wpa_supplicant( 1178): Add randomness: count=221 entropy=215
D/wpa_supplicant( 1178): Add randomness: count=222 entropy=216
D/wpa_supplicant( 1178): Add randomness: count=223 entropy=217
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 ,freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=224 entropy=218
D/wpa_supplicant( 1178): Add randomness: count=225 entropy=219
D/wpa_supplicant( 1178): Add randomness: count=226 entropy=220
D/wpa_supplicant( 1178): Add randomness: count=227 entropy=221
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000616392600
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000616392637
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000616392626
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000599315226
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wif,i.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 616392600, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 616392637, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 616392626, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 599315226, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1241): sku_id=99
,D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/PMS     (  901): acquireWL(42840e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=630466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42840e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0,
D/wpa_supplicant( 1178): Add randomness: count=228 entropy=222
D/wpa_supplicant( 1178): Add randomness: count=229 entropy=223
D/wpa_supplicant( 1178): Add randomness: count=230 entropy=224
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=231 entropy=225
,D/wpa_supplicant( 1178): Add randomness: count=232 entropy=226
D/wpa_supplicant( 1178): Add randomness: count=233 entropy=227
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
,W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000633795051
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000633795078
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000616392626
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000599315226
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 633795051, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 633795078, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 616392626, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 599315226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42839eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10073}
,V/AlarmManager(  901): sending alarm PendingIntent{425ed688: PendingIntentRecord{425d2ef8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454935574972, Int=0
,D/PMS     (  901): releaseWL(42839eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3932): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3932): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3932): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3932): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3932): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=234 entropy=228
D/wpa_supplicant( 1178): Add randomness: count=235 entropy=229
D/wpa_supplicant( 1178): Add randomness: count=236 entropy=230
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=237 entropy=231
D/wpa_supplicant( 1178): Add randomness: count=238 entropy=232
D/wpa_supplicant( 1178): Add randomness: count=239 entropy=233
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000650912074
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000650912099
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-73
I/wpa_supplicant( 1178): tsf=0000000599315226
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 650912074, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 650912099, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 599315226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4290b6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4290b6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(42912f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10073}
,V/AlarmManager(  901): sending alarm PendingIntent{4251fb48: PendingIntentRecord{4265d990 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454935590147, Int=0
,D/PMS     (  901): releaseWL(42912f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3932): [1] 5.onFinished: Installation state replication succeeded.
,D/Process (  901): killProcessQuiet, pid=4059
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4059:com.google.android.talk/u0a111 (adj 15): empty #17
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/ActivityManager(  901): Recipient 4059
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=240 entropy=234
D/wpa_supplicant( 1178): Add randomness: count=241 entropy=235
D/wpa_supplicant( 1178): Add randomness: count=242 entropy=236
D/wpa_supplicant( 1178): Add randomness: count=243 entropy=237
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=244 entropy=238
D/wpa_supplicant( 1178): Add randomness: count=245 entropy=239
D/wpa_supplicant( 1178): Add randomness: count=246 entropy=240
D/wpa_supplicant( 1178): Add randomness: count=247 entropy=241
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000668324467
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000668324506
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000599315226
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=8
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000668324494
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 668324467, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 668324506, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 599315226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 668324494, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42945158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42945158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=248 entropy=242
D/wpa_supplicant( 1178): Add randomness: count=249 entropy=243
D/wpa_supplicant( 1178): Add randomness: count=250 entropy=244
D/wpa_supplicant( 1178): Add randomness: count=251 entropy=245
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=252 entropy=246
D/wpa_supplicant( 1178): Add randomness: count=253 entropy=247
D/wpa_supplicant( 1178): Add randomness: count=254 entropy=248
D/wpa_supplicant( 1178): Add randomness: count=255 entropy=249
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000685715177
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000685715214
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000599315226
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=8
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000685715204
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 685715177, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 685715214, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 599315226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 685715204, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4295df30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=690466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4295df30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=256 entropy=250
D/wpa_supplicant( 1178): Add randomness: count=257 entropy=251
D/wpa_supplicant( 1178): Add randomness: count=258 entropy=252
D/wpa_supplicant( 1178): Add randomness: count=259 entropy=253
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=260 entropy=254
D/wpa_supplicant( 1178): Add randomness: count=261 entropy=255
D/wpa_supplicant( 1178): Add randomness: count=262 entropy=256
D/wpa_supplicant( 1178): Add randomness: count=263 entropy=257
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
,I/wpa_supplicant( 1178): tsf=0000000703105196
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000703105233
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-85
I/wpa_supplicant( 1178): tsf=0000000703105243
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=8
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000703105223
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 703105196, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 703105233, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 703105243, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 703105223, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=264 entropy=258
D/wpa_supplicant( 1178): Add randomness: count=265 entropy=259
D/wpa_supplicant( 1178): Add randomness: count=266 entropy=260
D/wpa_supplicant( 1178): Add randomness: count=267 entropy=261
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=268 entropy=262
D/wpa_supplicant( 1178): Add randomness: count=269 entropy=263
D/wpa_supplicant( 1178): Add randomness: count=270 entropy=264
D/wpa_supplicant( 1178): Add randomness: count=271 entropy=265
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  901): getDiscoveryDongleList
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000720491762
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000720491798
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
,I/wpa_supplicant( 1178): level=-85
I/wpa_supplicant( 1178): tsf=0000000720491808
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=8
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000720491787
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 720491762, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 720491798, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 720491808, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 720491787, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42982430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42982430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=272 entropy=266
D/wpa_supplicant( 1178): Add randomness: count=273 entropy=267
D/wpa_supplicant( 1178): Add randomness: count=274 entropy=268
D/wpa_supplicant( 1178): Add randomness: count=275 entropy=269
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=276 entropy=270
D/wpa_supplicant( 1178): Add randomness: count=277 entropy=271
D/wpa_supplicant( 1178): Add randomness: count=278 entropy=272
D/wpa_supplicant( 1178): Add randomness: count=279 entropy=273
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000737874918
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000737874954
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-85
I/wpa_supplicant( 1178): tsf=0000000737874966
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=8
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000737874944
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 737874918, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 737874954, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 737874966, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 737874944, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4260a378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=750466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4260a378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=280 entropy=274
D/wpa_supplicant( 1178): Add randomness: count=281 entropy=275
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=282 entropy=276
D/wpa_supplicant( 1178): Add randomness: count=283 entropy=277
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (489) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000737874918
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000754982259
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-85
I/wpa_supplicant( 1178): tsf=0000000737874966
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=8
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000737874944
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 737874918, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  901): InactiveState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiP2pService(  901): DefaultState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 754982259, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 737874966, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
V/ScoreHelper(  901): Only print Top 10 in ApScanList,
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 737874944, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=284 entropy=278
D/wpa_supplicant( 1178): Add randomness: count=285 entropy=279
D/wpa_supplicant( 1178): Add randomness: count=286 entropy=280
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=287 entropy=281
D/wpa_supplicant( 1178): Add randomness: count=288 entropy=282
D/wpa_supplicant( 1178): Add randomness: count=289 entropy=283
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000772412026
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000772412052
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000772412063
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####,
D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 772412026, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 772412052, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 772412063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter,
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=290 entropy=284
D/wpa_supplicant( 1178): Add randomness: count=291 entropy=285
D/wpa_supplicant( 1178): Add randomness: count=292 entropy=286
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
,I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=293 entropy=287
D/wpa_supplicant( 1178): Add randomness: count=294 entropy=288
D/wpa_supplicant( 1178): Add randomness: count=295 entropy=289
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000789795199
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000789795225
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000789795236
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/w,pa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 789795199, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 789795225, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 789795236, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
,D/WirelessDisplayService(  901): getDiscoveryDongleList
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
V/ScoreHelper(  901):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000),
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/PMS     (  901): acquireWL(4261f7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(4261f7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
,I/HtcPowerSaver(  901): >> updateStatus
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
,D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=296 entropy=290
D/wpa_supplicant( 1178): Add randomness: count=297 entropy=291
D/wpa_supplicant( 1178): Add randomness: count=298 entropy=292
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=299 entropy=293
D/wpa_supplicant( 1178): Add randomness: count=300 entropy=294
D/wpa_supplicant( 1178): Add randomness: count=301 entropy=295
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
,I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000807191968
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000807191995
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
,I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-80
I/wpa_supplicant( 1178): tsf=0000000807192006
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 807191968, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 807191995, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 807192006, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults,
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4271a7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=810466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4271a7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=302 entropy=296
D/wpa_supplicant( 1178): Add randomness: count=303 entropy=297
D/wpa_supplicant( 1178): Add randomness: count=304 entropy=298
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=305 entropy=299
D/wpa_supplicant( 1178): Add randomness: count=306 entropy=300
D/wpa_supplicant( 1178): Add randomness: count=307 entropy=301
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000824622008
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000824622034
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000824622045
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 824622008, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 824622034, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 824622045, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4234ec00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(4234ec00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=308 entropy=302
D/wpa_supplicant( 1178): Add randomness: count=309 entropy=303
D/wpa_supplicant( 1178): Add randomness: count=310 entropy=304
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=311 entropy=305
D/wpa_supplicant( 1178): Add randomness: count=312 entropy=306
D/wpa_supplicant( 1178): Add randomness: count=313 entropy=307
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.andro,id.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000841984957
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000841984983
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000841984994
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 841984957, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 841984983, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 841984994, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4290db48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4290db48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=314 entropy=308
D/wpa_supplicant( 1178): Add randomness: count=315 entropy=309
D/wpa_supplicant( 1178): Add randomness: count=316 entropy=310
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
,I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=317 entropy=311
D/wpa_supplicant( 1178): Add randomness: count=318 entropy=312
D/wpa_supplicant( 1178): Add randomness: count=319 entropy=313
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
,W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000859384958
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000859384984
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000859384995
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 859384958, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 859384984, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 859384995, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList,
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(428ef258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=870466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(428ef258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=320 entropy=314
D/wpa_supplicant( 1178): Add randomness: count=321 entropy=315
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=322 entropy=316
D/wpa_supplicant( 1178): Add randomness: count=323 entropy=317
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (376) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000876462403
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====,
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000876462428
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000859384995
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 876462403, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 876462428, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 859384995, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=324 entropy=318
D/wpa_supplicant( 1178): Add randomness: count=325 entropy=319
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=326 entropy=320
D/wpa_supplicant( 1178): Add randomness: count=327 entropy=321
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (238) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000893852266
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000893852292
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 893852266, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 893852292, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 2 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (2) end of scan result ==,
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=328 entropy=322
D/wpa_supplicant( 1178): Add randomness: count=329 entropy=323
D/wpa_supplicant( 1178): Add randomness: count=330 entropy=324
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
,I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
,I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=331 entropy=325
D/wpa_supplicant( 1178): Add randomness: count=332 entropy=326
D/wpa_supplicant( 1178): Add randomness: count=333 entropy=327
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (351) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000911234993
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
,I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000911235032
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=9
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000911235020
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 911234993, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 911235032, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 911235020, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4297ffc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  901): n_update end
D/UsbnetService(  901): BroadcastReceiver::onReceive+
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  901): releaseWL(4297ffc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=334 entropy=328
D/wpa_supplicant( 1178): Add randomness: count=335 entropy=329
D/wpa_supplicant( 1178): Add randomness: count=336 entropy=330
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=337 entropy=331
D/wpa_supplicant( 1178): Add randomness: count=338 entropy=332
D/wpa_supplicant( 1178): Add randomness: count=339 entropy=333
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelemen,t id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (351) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000911234993
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000928462565
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=9
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000928462555
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 911234993, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 928462565, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 928462555, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1,
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(428f1f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000},
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=930466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(428f1f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=340 entropy=334
D/wpa_supplicant( 1178): Add randomness: count=341 entropy=335
D/wpa_supplicant( 1178): Add randomness: count=342 entropy=336
D/wpa_supplicant( 1178): Add randomness: count=343 entropy=337
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 ,freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=344 entropy=338
D/wpa_supplicant( 1178): Add randomness: count=345 entropy=339
D/wpa_supplicant( 1178): Add randomness: count=346 entropy=340
D/wpa_supplicant( 1178): Add randomness: count=347 entropy=341
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (490) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000945712276
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000945712312
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=9
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000945712302
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-75
I/wpa_supplicant( 1178): tsf=0000000945712321
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wi,fi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 945712276, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 945712312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 945712302, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 945712321, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults,
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=348 entropy=342
D/wpa_supplicant( 1178): Add randomness: count=349 entropy=343
D/wpa_supplicant( 1178): Add randomness: count=350 entropy=344
D/wpa_supplicant( 1178): Add randomness: count=351 entropy=345
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=352 entropy=346
D/wpa_supplicant( 1178): Add randomness: count=353 entropy=347
D/wpa_supplicant( 1178): Add randomness: count=354 entropy=348
D/wpa_supplicant( 1178): Add randomness: count=355 entropy=349
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (490) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000962882099
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000962882135
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=9
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000962882124
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-75
I/wpa_supplicant( 1178): tsf=0000000962882145
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 962882099, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 962882135, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 962882124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 962882145, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42884120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  901): n_update end
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(42884120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
,I/HtcPowerSaver(  901): >> updateStatus
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=356 entropy=350
D/wpa_supplicant( 1178): Add randomness: count=357 entropy=351
D/wpa_supplicant( 1178): Add randomness: count=358 entropy=352
D/wpa_supplicant( 1178): Add randomness: count=359 entropy=353
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=360 entropy=354
D/wpa_supplicant( 1178): Add randomness: count=361 entropy=355
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1178): Add randomness: count=362 entropy=356
D/wpa_supplicant( 1178): Add randomness: count=363 entropy=357
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (490) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000980275160
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000980275199
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
,I/wpa_supplicant( 1178): id=9
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000980275189
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-75
I/wpa_supplicant( 1178): tsf=0000000980275209
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 980275160, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 980275199, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 980275189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 980275209, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(426eb440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=990466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(426eb440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=364 entropy=358
D/wpa_supplicant( 1178): Add randomness: count=365 entropy=359
D/wpa_supplicant( 1178): Add randomness: count=366 entropy=360
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=367 entropy=361
D/wpa_supplicant( 1178): Add randomness: count=368 entropy=362
D/wpa_supplicant( 1178): Add randomness: count=369 entropy=363
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (490) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000000997392280
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
,I/wpa_supplicant( 1178): tsf=0000000997392304
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=9
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000000980275189
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-75
I/wpa_supplicant( 1178): tsf=0000000997392315
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 997392280, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 997392304, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 980275189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 997392315, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4283d9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,D/ConnectivityService(  901): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  901): sending alarm PendingIntent{41dfe118: PendingIntentRecord{42475cb0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783497, Int=0
,V/AlarmManager(  901): sending alarm PendingIntent{41ff2348: PendingIntentRecord{425c7310 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928979, Int=0
,D/PMS     (  901): acquireWL(42935108): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,V/AlarmManager(  901): sending alarm PendingIntent{42554e28: PendingIntentRecord{42548648 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454935862446, Int=900000
D/ConnectivityService(  901): Done.
D/ConnectivityService(  901): Setting timer for 720seconds
,V/AlarmManager(  901): sending alarm PendingIntent{41bfe3e8: PendingIntentRecord{426f2080 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454935940497, Int=0
,D/PMS     (  901): releaseWL(42935108): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  901): acquireWL(429679b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,W/ContextImpl( 4229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  901): releaseWL(429679b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4229): call getInstance()
,D/SmartSyncUtils( 4229): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4229): MY_DEBUG = false
D/PMS     (  901): acquireWL(42902de0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4229 1000 null
D/PMS     (  901): releaseWL(4283d9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4229): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4229): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 1, nEnd = 2, bNormalRange = true
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,D/SmartSyncScreenOnOffTimeReceiver( 4229): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 2
,W/ContextImpl( 4229): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
I/FeedHostManager( 1266): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,D/SmartSyncScreenOnOffTimeReceiver( 4229): AlarmOnTime = -1
,I/FeedHostManager( 1266): NightMode begin at 0, end at 7
D/PMS     (  901): acquireWL(42777b60): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1266 10075 null
,D/SmartSyncScreenOnOffTimeReceiver( 4229): SettingOnTime = 1454979600000, randomSettingOnTime = 1454978625000
,D/SmartSyncScreenOnOffTimeReceiver( 4229): SettingOffTime = 1454976000000, randomSettingOffTime = 1454976530000
,I/FeedHostManager( 1266): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1454935940673, BeginTime: 1454972400000, EndTime: 1454997600000
,D/SmartSyncScreenOnOffTimeReceiver( 4229): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4229): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4229): bNightModeTurnOffOnce = false
D/PMS     (  901): releaseWL(42777b60): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  901): releaseWL(42902de0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,D/PMS     (  901): acquireWL(4295f500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4295f500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=370 entropy=364
D/wpa_supplicant( 1178): Add randomness: count=371 entropy=365
D/wpa_supplicant( 1178): Add randomness: count=372 entropy=366
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=373 entropy=367
D/wpa_supplicant( 1178): Add randomness: count=374 entropy=368
D/wpa_supplicant( 1178): Add randomness: count=375 entropy=369
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001014823213
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001014823237
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
,I/wpa_supplicant( 1178): level=-82
I/wpa_supplicant( 1178): tsf=0000001014823248
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1014823213, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1014823237, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 1014823248, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (3) end of scan result ==,
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4260a170): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  901): handleInetConditionChange: starting a change hold
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  901): releaseWL(4260a170): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  901): acquireWL(427650d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  901): releaseWL(427650d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  901): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  901): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
,D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50,
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=376 entropy=370
D/wpa_supplicant( 1178): Add randomness: count=377 entropy=371
D/wpa_supplicant( 1178): Add randomness: count=378 entropy=372
D/wpa_supplicant( 1178): Add randomness: count=379 entropy=373,
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
,I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
,D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=380 entropy=374
D/wpa_supplicant( 1178): Add randomness: count=381 entropy=375
D/wpa_supplicant( 1178): Add randomness: count=382 entropy=376
D/wpa_supplicant( 1178): Add randomness: count=383 entropy=377
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (491) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001032248652
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001032248693
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
,I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-82
I/wpa_supplicant( 1178): tsf=0000001032248704
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=11
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001032248681
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1032248652, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1032248693, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 1032248704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1032248681, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4254f658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4254f658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  901): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1113): closing low battery warning: level=100
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
,D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-,
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=384 entropy=378
D/wpa_supplicant( 1178): Add randomness: count=385 entropy=379
D/wpa_supplicant( 1178): Add randomness: count=386 entropy=380
D/wpa_supplicant( 1178): Add randomness: count=387 entropy=381
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=388 entropy=382
D/wpa_supplicant( 1178): Add randomness: count=389 entropy=383
D/wpa_supplicant( 1178): Add randomness: count=390 entropy=384
D/wpa_supplicant( 1178): Add randomness: count=391 entropy=385
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (491) for get BSS: id=0,
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001032248652
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001049635162
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-77
I/wpa_supplicant( 1178): tsf=0000001032248704
,I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=11
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001049635172
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1032248652, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1049635162, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1032248704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1049635172, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(425b8c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1050465, Int=0,
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  901): releaseWL(425b8c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS,
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
,I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1178): Add randomness: count=392 entropy=386
D/wpa_supplicant( 1178): Add randomness: count=393 entropy=387
D/wpa_supplicant( 1178): Add randomness: count=394 entropy=388
D/wpa_supplicant( 1178): Add randomness: count=395 entropy=389
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
,I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
,I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
,I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=396 entropy=390
D/wpa_supplicant( 1178): Add randomness: count=397 entropy=391
,D/wpa_supplicant( 1178): Add randomness: count=398 entropy=392
D/wpa_supplicant( 1178): Add randomness: count=399 entropy=393
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
,W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (491) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001066892189
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001066892215
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700,
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-77
I/wpa_supplicant( 1178): tsf=0000001032248704
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
,I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=11
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001066892226
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1066892189, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1066892215, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1032248704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1066892226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
,I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=400 entropy=394
D/wpa_supplicant( 1178): Add randomness: count=401 entropy=395
,D/wpa_supplicant( 1178): Add randomness: count=402 entropy=396
D/wpa_supplicant( 1178): Add randomness: count=403 entropy=397
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
,I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
,I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1,
I/wpa_supplicant( 1178): isConcurrentMode() is 0
,I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
,I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,D/wpa_supplicant( 1178): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=404 entropy=398
D/wpa_supplicant( 1178): Add randomness: count=405 entropy=399
D/wpa_supplicant( 1178): Add randomness: count=406 entropy=400
D/wpa_supplicant( 1178): Add randomness: count=407 entropy=401
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (491) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001084284948
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001084284975
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-77
I/wpa_supplicant( 1178): tsf=0000001032248704
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=11
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001084284985
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1084284948, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1084284975, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1032248704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1084284985, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(427b6c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(427b6c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
,D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
,D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=408 entropy=402
,D/wpa_supplicant( 1178): Add randomness: count=409 entropy=403
D/wpa_supplicant( 1178): Add randomness: count=410 entropy=404
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
,D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
,I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=411 entropy=405
D/wpa_supplicant( 1178): Add randomness: count=412 entropy=406
D/wpa_supplicant( 1178): Add randomness: count=413 entropy=407
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (491) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001101674961
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001101674988
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=10
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-77
I/wpa_supplicant( 1178): tsf=0000001032248704
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=11
,I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001101674999
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1101674961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1101674988, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1032248704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1101674999, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 4 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (4) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4279c090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1110466, Int=0,
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4279c090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=414 entropy=408
D/wpa_supplicant( 1178): Add randomness: count=415 entropy=409
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1178): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=416 entropy=410
D/wpa_supplicant( 1178): Add randomness: count=417 entropy=411
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): W,PS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  901): getDiscoveryDongleList
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (352) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001119054967
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001119054994
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=11
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001101674999,
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ####
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1119054967, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1119054994, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 1101674999, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(427ba938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(427ba938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  901): updateBatteryInfo
,D/PowerUI ( 1113): closing low battery warning: level=100
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=418 entropy=412
D/wpa_supplicant( 1178): Add randomness: count=419 entropy=413
D/wpa_supplicant( 1178): Add randomness: count=420 entropy=414
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=421 entropy=415
D/wpa_supplicant( 1178): Add randomness: count=422 entropy=416
D/wpa_supplicant( 1178): Add randomness: count=423 entropy=417
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001136452110
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001136452136
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-86
I/wpa_supplicant( 1178): tsf=0000001136452146
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1136452110, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1136452136, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 1136452146, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42754420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): releaseWL(42754420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/ContextImpl( 4229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3755): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3755): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3755): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3755): Cust_ConnectToPC   : spcsc>false
D/        ( 3755): Cust_ConnectToPC   : IPT>true
,D/        ( 3755): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3755): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3755): Index of the first 1 = 3
W/Settings( 3755): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3755): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3755): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3755): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3755): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3755): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
D/SmartNS_Utility( 3755): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  901): acquireWL(42953368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
D/UsbnetService(  901): BroadcastReceiver::onReceive+
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(42953368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
,I/HtcPowerSaver(  901): >> updateStatus
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=424 entropy=418
D/wpa_supplicant( 1178): Add randomness: count=425 entropy=419
D/wpa_supplicant( 1178): Add randomness: count=426 entropy=420
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=427 entropy=421
D/wpa_supplicant( 1178): Add randomness: count=428 entropy=422
D/wpa_supplicant( 1178): Add randomness: count=429 entropy=423
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  901): [MLHD] enter h,andleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001153854929
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001153854955
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
,I/wpa_supplicant( 1178): level=-80
I/wpa_supplicant( 1178): tsf=0000001153854966
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WirelessDisplayService(  901): getDiscoveryDongleList
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1153854929, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1153854955, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 1153854966, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  901): acquireWL(42840490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1170466, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42840490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=430 entropy=424
D/wpa_supplicant( 1178): Add randomness: count=431 entropy=425
D/wpa_supplicant( 1178): Add randomness: count=432 entropy=426
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=433 entropy=427
D/wpa_supplicant( 1178): Add randomness: count=434 entropy=428
D/wpa_supplicant( 1178): Add randomness: count=435 entropy=429
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE,
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1,
I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001171281856
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001171281883
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-85
,I/wpa_supplicant( 1178): tsf=0000001171281894
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos,
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1171281856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1171281883, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 1171281894, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=436 entropy=430
D/wpa_supplicant( 1178): Add randomness: count=437 entropy=431
D/wpa_supplicant( 1178): Add randomness: count=438 entropy=432
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=439 entropy=433
D/wpa_supplicant( 1178): Add randomness: count=440 entropy=434
D/wpa_supplicant( 1178): Add randomness: count=441 entropy=435
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001188675011
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001188675038
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-77
I/wpa_supplicant( 1178): tsf=0000001188675049
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  901): Only print Top 10 in ApScanList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1188675011, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1188675038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1188675049, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42949500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42949500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=442 entropy=436
D/wpa_supplicant( 1178): Add randomness: count=443 entropy=437
D/wpa_supplicant( 1178): Add randomness: count=444 entropy=438
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
,I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
,D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56,
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=445 entropy=439
D/wpa_supplicant( 1178): Add randomness: count=446 entropy=440
D/wpa_supplicant( 1178): Add randomness: count=447 entropy=441
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001206064948
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001206064974
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412,
I/wpa_supplicant( 1178): level=-77
I/wpa_supplicant( 1178): tsf=0000001206064985
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  901): Only print Top 10 in ApScanList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1206064948, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1206064974, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1206064985, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4296aaa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PMS     (  901): releaseWL(4296aaa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory),
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz,
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
,I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83,
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=448 entropy=442
D/wpa_supplicant( 1178): Add randomness: count=449 entropy=443
D/wpa_supplicant( 1178): Add randomness: count=450 entropy=444
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
,I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
,I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46,
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=451 entropy=445
D/wpa_supplicant( 1178): Add randomness: count=452 entropy=446
D/wpa_supplicant( 1178): Add randomness: count=453 entropy=447
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001223475019
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001223475045
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-83
I/wpa_supplicant( 1178): tsf=0000001223475056
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1223475019, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1223475045, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1223475056, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
,D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(427677b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000},
,V/AlarmManager(  901): sending alarm PendingIntent{42373c30: PendingIntentRecord{4237ef90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1230466, Int=0,
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(427677b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=454 entropy=448
D/wpa_supplicant( 1178): Add randomness: count=455 entropy=449
D/wpa_supplicant( 1178): Add randomness: count=456 entropy=450
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=457 entropy=451
D/wpa_supplicant( 1178): Add randomness: count=458 entropy=452
D/wpa_supplicant( 1178): Add randomness: count=459 entropy=453
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001240825142
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001240825169
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-83
I/wpa_supplicant( 1178): tsf=0000001240825182
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1240825142, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1240825169, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 1240825182, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults,
V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
D/WifiStateMachine(  901): == (3) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=460 entropy=454
D/wpa_supplicant( 1178): Add randomness: count=461 entropy=455
D/wpa_supplicant( 1178): Add randomness: count=462 entropy=456
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=463 entropy=457
D/wpa_supplicant( 1178): Add randomness: count=464 entropy=458
D/wpa_supplicant( 1178): Add randomness: count=465 entropy=459
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
,I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001258221765
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001258221792
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-87
I/wpa_supplicant( 1178): tsf=0000001258221803
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList,
D/WifiP2pService(  901): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1258221765, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1258221792, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  901): Only print Top 10 in ApScanList
,V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  901):  + computeScore(NG700): 1,
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 1258221803, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 3 to mScanResults
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(428578e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(428578e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(4288c188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4288c188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  901): updateBatteryInfo
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=466 entropy=460
D/wpa_supplicant( 1178): Add randomness: count=467 entropy=461
D/wpa_supplicant( 1178): Add randomness: count=468 entropy=462
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 9
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1178): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=469 entropy=463
,D/wpa_supplicant( 1178): Add randomness: count=470 entropy=464
D/wpa_supplicant( 1178): Add randomness: count=471 entropy=465
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  901): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (377) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-46
I/wpa_supplicant( 1178): tsf=0000001275624865
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-56
I/wpa_supplicant( 1178): tsf=0000001275624892
,I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=12
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-87
I/wpa_supplicant( 1178): tsf=0000001275624903
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  901): getDiscoveryDongleList
,D/WifiStateMachine(  901): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1275624865, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1275624892, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 1275624903, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  901): add 3 to mScanResults
V/ScoreHelper(  901): Only print Top 10 in ApScanList
V/ScoreHelper(  901):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  901):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  901):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  901):  + computeScore(NG700): 1
D/WifiStateMachine(  901): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (3) end of scan result ==
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4304): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4304): ====startRecUseTime====
D/htc.customization.log.level( 4304):  is 
W/CustomizationLogLevel( 4304): Level value is invalid, use default level 2
D/CustomizationManager( 4304):  Read ACC file spent 0.138 (s)
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4304): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4304): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4304): Parsing tag category name = system
I/CustomizationCIDLoader( 4304): Parsing tag category name = application
I/CustomizationCIDLoader( 4304): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4304): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4304): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4304): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4304): Parsing tag category name = Settings
D/CustomizationManager( 4304):  Read CID file spent 0.198 (s)
D/CustomizationManager( 4304):  All configurations done spent 0.198 (s)
W/HtcNativeFlag( 4304): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4304): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4304): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4304): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  901): deletePackageAsUser: pkg=com.test.thalitest, pid=4304, uid=2000 user=0
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  901): Skipping PackageSetting{422ec168 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1880): Unregistering com.test.thalitest
E/acms    ( 1880): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1468): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  901): acquireWL(42a21e28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1468 10028 null
W/PackageManager(  901): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  901): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/PMS     (  901): releaseWL(42a21e28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "sms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "smsto"
D/VoicemailCleanupService( 1294): Cleaning up data for package: com.test.thalitest
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mmsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PackageBroadcastService( 1221): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "sms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  901): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4318 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "smsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  901):   Scheme: "mms"
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/InputMethodManagerService(  901): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/MultiDex( 4318): install
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mmsto"
I/MultiDex( 4318): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
F/PackageManager(  901): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  901): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager(  901): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager(  901): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager(  901): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  901): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  901): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  901): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  901): 	at com.android.internal.util.FastXmlSerializer.escapeAndAppendString(FastXmlSerializer.java:145)
F/PackageManager(  901): 	at com.android.internal.util.FastXmlSerializer.attribute(FastXmlSerializer.java:176)
F/PackageManager(  901): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1203)
F/PackageManager(  901): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  901): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  901): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  901): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  901): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  901): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  901): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager(  901): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  901): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager(  901): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager(  901): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager(  901): 	... 14 more
I/MultiDex( 4318): loading existing secondary dex files
I/MultiDex( 4318): load found 1 secondary dex files
I/MultiDex( 4318): install done
D/UserBehaviorLoggingService(  901): [getSecurityProperties] Access Denied, Unknown pacakage name!
D/ErrorReport(  901): HtcErrorReportManager Begin---add error logs to dropbox
I/PackageManager(  901): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/ErrorReport(  901): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  901): java.lang.IllegalArgumentException: key == null
E/ErrorReport(  901): 	at javax.crypto.spec.SecretKeySpec.<init>(SecretKeySpec.java:59)
E/ErrorReport(  901): 	at com.htc.utils.ulog.io.LogStream$CipherStream.getCipherOutputStream(LogStream.java:223)
E/ErrorReport(  901): 	at com.htc.utils.ulog.io.LogStream.concatenateOutputStream(LogStream.java:101)
E/ErrorReport(  901): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:389)
E/ErrorReport(  901): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  901): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  901): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  901): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  901): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  901): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  901): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  901): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  901): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  901): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  901): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  901): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  901): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  901): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  901): 	at dalvik.system.NativeStart.run(Native Method)
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  901): Delaying start of: ServiceRecord{42635988 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 1221): CP2 sync disabled
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1221, uid=10028, userID:0
D/PMS     (  901): acquireWL(42466940): PARTIAL_WAKE_LOCK  Icing 0x1 1221 10028 null
I/Icing   ( 1221): doRemovePackageData com.test.thalitest
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1221): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1221): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1221): Writing status failed
D/PMS     (  901): releaseWL(42466940): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4318): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  901): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4340 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  901): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
E/SQLiteDatabase( 1221): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1221): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1221): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1221): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1221): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1221): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1221): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1221): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1221): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1221): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1221): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1221): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4340): install
E/ClearPendingStateOp( 1221): Runtime exception while performing operation
E/ClearPendingStateOp( 1221): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1221): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1221): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1221): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1221): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1221): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1221): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1221): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1221): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1221): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1221): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4340): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
F/ClearPendingStateOp( 1221): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1221): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1221): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1221): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1221): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1221): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1221): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1221): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1221): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1221): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1221): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1221): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4340): loading existing secondary dex files
I/MultiDex( 4340): load found 1 secondary dex files
I/MultiDex( 4340): install done
I/ProviderInstaller( 4340): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/DropBoxManagerService(  901): Can't write: system_app_wtf
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
I/ActivityManager(  901): Resuming delayed broadcast
E/SharedPreferencesImpl( 1205): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1392): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1392): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1392): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca3e8d0
I/ActivityManager(  901): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
W/[PluginManager]RegisterService( 1392): provider may killed!
W/[PluginManager]RegisterService( 1392): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1392): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1392): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1392): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1392): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1392): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1392): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1392): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1392): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1392): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1392): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1392): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1392): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1392): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1392): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1392): handle notify Blinkfeed plugin client changed
I/ActivityManager(  901): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1266): action: android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 4318): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4318): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4318): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4318): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4318): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4318): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4318): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4318): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4318): threadid=12: thread exiting with uncaught exception (group=0x4170ae30)
I/ActivityManager(  901): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/AndroidRuntime( 4318): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4318): Process: com.google.android.gms.drive, PID: 4318
E/AndroidRuntime( 4318): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4318): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4318): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4318): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4318): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4318): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4318): 	at ctn.run(SourceFile:985)
I/IcingCorporaProvider( 2901): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ActivityManager(  901): App crashed! Process: com.google.android.gms.drive
D/Process ( 4318): killProcess, pid=4318
D/Process ( 4318): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
E/SQLiteLog( 2901): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2901): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5cadd8f8
W/dalvikvm( 2901): threadid=14: thread exiting with uncaught exception (group=0x4170ae30)
I/ActivityManager(  901): Recipient 4318
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Process com.google.android.gms.drive (pid 4318) has died.
W/ActivityManager(  901): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  901): Resuming delayed broadcast
E/AndroidRuntime( 2901): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2901): Process: com.google.android.googlequicksearchbox:search, PID: 2901
E/AndroidRuntime( 2901): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2901): 	at cid.d(PG:186)
E/AndroidRuntime( 2901): 	at clo.g(PG:594)
E/AndroidRuntime( 2901): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2901): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2901): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2901): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2901): 	at clr.tL(PG:827)
E/AndroidRuntime( 2901): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2901): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2901): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2901): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  901): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  901): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4361 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/Process ( 2901): killProcess, pid=2901
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
D/Process ( 2901): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
W/PackageManager(  901): Unable to load service info ResolveInfo{428c2c20 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  901): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  901): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  901): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  901): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  901): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  901): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  901): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  901): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  901): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  901): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  901): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  901): 	at dalvik.system.NativeStart.main(Native Method)
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  901): Client com.google.android.googlequicksearchbox (pid 2901): Died!
I/ActivityManager(  901): Recipient 2901
I/ActivityManager(  901): Process com.google.android.googlequicksearchbox:search (pid 2901) has died.
W/ActivityManager(  901): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  901): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/WifiService(  901): Client connection lost with reason: 4
E/SQLiteDatabase( 1221): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 1221): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1221): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1221): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1221): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 1221): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 1221): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 1221): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 1221): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 1221): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 1221): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 1221): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 1221): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 1221): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 1221): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 1221): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1221): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1221): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 1221): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 1221): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1221): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1221): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1221): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 1221): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 1221): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 1221): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 1221): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 1221): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 1221): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 1221): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 1221): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 1221): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 1221): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 1221): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1221): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1221): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 1221): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 1221): threadid=10: thread exiting with uncaught exception (group=0x4170ae30)
E/AndroidRuntime( 1221): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 1221): Process: com.google.android.gms, PID: 1221
E/AndroidRuntime( 1221): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1221): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 1221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 1221): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1221): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 1221): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 1221): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1221): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 1221): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 1221): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 1221): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 1221): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 1221): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 1221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1221): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1221): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  901): App crashed! Process: com.google.android.gms
D/Process (  901): killProcessQuiet, pid=1221
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
W/ActivityManager(  901): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  901): Killing 1221:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1266): loadItems() com.htc.launcher.pageview.WidgetManager@41bcde78 +
I/Prism.WidgetManager( 1266): onLoadItems() +
D/WifiService(  901): Client connection lost with reason: 4
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4361): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4361): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4361): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4361): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4361): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4361): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4361): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4361): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4361): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4361): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4361): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4361): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4361): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4361): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4361): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4361): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4361): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4361): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4361): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4361): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4361): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4361): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4361): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4361): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4361): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4361): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4361): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4361): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4361): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4361): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4361): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4361): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4361): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4361): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4361): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4361): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4361): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4361): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4361): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4361): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4361): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4361): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4361): Opened ClientFlag.db in read-only mode
D/RemoteDisplayProvider(  901): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
E/SQLiteDatabase( 4361): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4361): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4361): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4361): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4361): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4361): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4361): threadid=11: thread exiting with uncaught exception (group=0x4170ae30)
D/RemoteDisplayProvider(  901): start
E/AndroidRuntime( 4361): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4361): Process: com.google.android.apps.docs, PID: 4361
E/AndroidRuntime( 4361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4361): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4361): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4361): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4361): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4361): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  901): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
E/SQLiteDatabase( 4361): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4361): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4361): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4361): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4361): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4361): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
,E/SQLiteDatabase( 4361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4361): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4361): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4361): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4361): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4361): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4361): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4361): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4361): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4361): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4361): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4361): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4361): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4361): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4361): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4361): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4361): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4361): Opened ClientFlag.db in read-only mode
I/ActivityManager(  901): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4380 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4361): killProcess, pid=4361
D/Process ( 4361): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/AtomicFile(  901): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/BroadcastQueue(  901): Skipping deliver [background] BroadcastRecord{42771960 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{427715c0 4361 com.google.android.apps.docs/10100/u0 remote:426bf790}: process crashing
W/AppWidgetServiceImpl(  901): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  901): Recipient 4361
D/Process (  901): killProcessQuiet, pid=3509
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Killing 3509:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  901): Process com.google.android.apps.docs (pid 4361) has died.

```
