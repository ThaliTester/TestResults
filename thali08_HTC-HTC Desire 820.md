#### Test 583805004f2b042_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1507): handler message = 4011
E/HtcModeClient( 1507): Check connection and retry 8 times.
,E/cutils-trace( 4264): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4264): ====startRecUseTime====
D/htc.customization.log.level( 4264):  is 
W/CustomizationLogLevel( 4264): Level value is invalid, use default level 2
D/CustomizationManager( 4264):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4264): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4264): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4264): Parsing tag category name = system
I/CustomizationCIDLoader( 4264): Parsing tag category name = application
I/CustomizationCIDLoader( 4264): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4264): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4264): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4264): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4264): Parsing tag category name = Settings
D/CustomizationManager( 4264):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4264):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4264): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4264): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4264): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4264): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4264
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/SensorManager(  905): mEventCount = 750
,D/PMS     (  905): acquireWL(424e8140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(424e8140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,I/CalendarProvider2( 1507): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1507): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(423f5e10): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3886 10154 null
,I/ActivityManager(  905): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3886): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 ,
,W/ContextImpl( 3886): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3886, uid=10154, userID:0
,I/MusicLeanback( 3886): Conditions not met for autocaching.
,I/MusicLeanback( 3886): Stop autocaching.
D/PMS     (  905): releaseWL(423f5e10): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4281 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4281): Loading default preferences
,W/Resources( 4281): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  905): New client listening to asynchronous messages
,D/SyncApplication( 4281): Overriding preferences with custom values
V/AlarmManager(  905): sending alarm PendingIntent{42385d00: PendingIntentRecord{4232f850 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=71757, Int=0
,D/SyncApplication( 4281): Updating preferences succeeded
,E/SyncApplication( 4281): Application created.
D/VolumeInfo( 4281): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4281): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4281): Found 0 mount point(s)
,V/VolumeInfo( 4281): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4281): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4281): getNewCalendarAuthority()...
,D/VolumeInfo( 4281): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4281): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4281): enableAppOperation()+
,D/SyncApplication( 4281): enableAppOperation()-
,D/HTCUtilities( 4281): isNeorSinged() + 
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4281, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4281, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4281): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4281): isNeorSinged() return false
,D/CDMountReceiver( 4281): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4281): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1582): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4281): enable CD Auto-mount: true
,D/HTCUtilities( 4281): enable auto-mount
,D/HTCUtilities( 4281): enable auto-mount
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
I/ActivityManager(  905): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  905): Resuming delayed broadcast
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b1c818 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 2 14 4 11
I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41ba0c68 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 10 3 16
,W/MediaManager( 3866): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3727
,I/ActivityManager(  905): Killing 3727:com.htc.sense.news/u0a75 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4305 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  905): Recipient 3727
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarApplication( 4305): onCreate
D/ProviderChangeReceiver( 4305): ---------------------------------------------------
,D/ProviderChangeReceiver( 4305): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4305): start to updateAlertNotification!
,I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4319 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=3905
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3905:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/AlertService( 4305): No fired or scheduled alerts
,D/HtcAlertUtils( 4305): -- cancelReminderNotification --
,D/HtcAlertUtils( 4305): broadcastExistReminder!
,D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  905): Recipient 3905
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 4319): [4319/4319] onCreate()
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/Process (  905): killProcessQuiet, pid=3937
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Killing 3937:com.htc.sdm/u0a80 (adj 15): empty #17
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=42 rxSum=31} preTxRxSum={txSum=34 rxSum=24}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19025 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19026 delay=15s
D/PMS     (  905): releaseWL(425efa50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3937
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/HtcModeClient( 1507): handler message = 4011
,E/HtcModeClient( 1507): Check connection and retry 9 times.
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{426eccc0 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:66, mTXpacketCount:66, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  905): releaseWL(4243b350): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/ClockThread( 1115): now=1455035759943 next=57
,I/ClockThread( 1115): now=1455035760000 next=60000
D/PMS     (  905): acquireWL(42618bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=76017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42618bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  905): mEventCount = 900
,I/HtcModeClient( 1507): handler message = 4011
,E/HtcModeClient( 1507): Check connection and retry 10 times.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/PMS     (  905): acquireWL(426265d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
,V/AlarmManager(  905): sending alarm PendingIntent{41fd4c30: PendingIntentRecord{41fd4bf8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455035764753, Int=0
,D/PMS     (  905): releaseWL(426265d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4160): [1] 5.onFinished: Installation state replication succeeded.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1507): handler message = 4011
,E/HtcModeClient( 1507): Check connection and retry 11 times.
,I/SensorManager(  905): mEventCount = 1050
,D/AutoSetting( 1401): service - mHandler: update timezone
,D/AutoSetting( 1401): service - handleMessage() stop self
,D/AutoSetting( 1401): service - handleMessage() quit looper
,D/AutoSetting( 1401): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3962
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3962:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3962
,D/WifiService(  905): Client connection lost with reason: 4
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1507): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1507): service - mHandler: update timezone
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1582): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1582): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c0b4a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 8 2 11
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=43 rxSum=32} preTxRxSum={txSum=42 rxSum=31}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19026 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19027 delay=15s
D/PMS     (  905): acquireWL(42627800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{423ac6b8: PendingIntentRecord{4232f850 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=87483, Int=0
D/PMS     (  905): releaseWL(42627800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/HtcModeClient( 1507): handler message = 4011
,E/HtcModeClient( 1507): Check connection and retry 12 times.
,I/SensorManager(  905): mEventCount = 1200
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:67, mTXpacketCount:66, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1507): handler message = 4011
,E/HtcModeClient( 1507): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1507): Don't start project servcice
,D/HtcModeClient( 1507): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1507): connectState: CONNECTION_READY = false
,D/SilentMusic( 1507): call stop
D/HtcModeClient( 1507): close connection
,W/HtcModeClient( 1507): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1507): read the terminate packet, so break
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72,
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true,
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  905): mEventCount = 1350
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42665888 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true,
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  905): acquireWL(426d7730): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,D/PMS     (  905): releaseWL(426d7730): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(426c3c38): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,D/PMS     (  905): releaseWL(426c3c38): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(426b6240): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,D/PMS     (  905): releaseWL(426b6240): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(426ad9e8): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,D/PMS     (  905): releaseWL(426ad9e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=44 rxSum=33} preTxRxSum={txSum=43 rxSum=32}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19027 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19028 delay=15s
D/PMS     (  905): acquireWL(426a1138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{426310c0: PendingIntentRecord{4232f850 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102488, Int=0
D/PMS     (  905): releaseWL(426a1138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4344 uid=10077 gids={50077}
D/PMS     (  905): acquireWL(4263f9c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
,V/AlarmManager(  905): sending alarm PendingIntent{42536678: PendingIntentRecord{425b98d8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455035787175, Int=60000
,D/PMS     (  905): releaseWL(4263f9c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4344): SMSBackupAgentService started
,D/SMSBackup( 4344): Checking restore status
,D/SMSBackup( 4344): Restore complete
,D/SMSBackup( 4344): cancelCheckAlarm
,D/SMSBackup( 4344): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=4000
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4000:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4000
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:71, mTXpacketCount:67, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  905): mEventCount = 1500
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420f5060
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  905): pid=905, uid=1000
,W/SensorService(  905): Active sensors: size = 2
,W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420f5060, eanble = 0, strlen(mName) = 59
,W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42322300
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@41bd63e0
W/PMS     (  905): mWirelessDisplayManager is null
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  905): setLight #0: color=#0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 369ms
,W/PnPMgr  (  358): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425b6e88)
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=1270
,D/PMN     (  905): wakingUp
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
,D/NfcService( 1256): applyRouting -2
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): acquireWL(42405420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,D/PMS     (  905): acquireWL(425ac3d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42405420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AlarmManager(  905): ACTION_SCREEN_ON
,D/PMS     (  905): releaseWL(425ac3d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/PMN     (  905): onScreenOn
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/MtpService( 2445): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2445): [MTP][onReceive]-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): acquireWL(426aece8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,D/PMS     (  905): releaseWL(426aece8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19029 delay=15s
,D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4363 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ClockThread( 1115): stop update clock
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
I/HtcPowerSaver(  905): << updateStatus
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:On
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
,D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,D/NetworkPolicy(  905): updateScreenOn: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(424a0c20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4363 1000 null
D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
,D/PMS     (  905): releaseWL(424a0c20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4363): getMobilePolicyEnabled, result = true
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1401): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1401): service - onCreate()
,D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/AutoSetting( 1401): service - AddressCache: using context: com.htc.Weather
D/PMS     (  905): acquireWL(42430040): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1826): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1826): onScreenOn: 1455035794765
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1826): onScreenOn: 1455035794765
,D/AutoSetting( 1401): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  905): request 42388c80 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,D/PMS     (  905): releaseWL(42430040): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42322300
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42322300, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@41bd63e0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/TetherSettings( 4220): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4220): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4220): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4220): Cust_ConnectToPC   : spcsc>false
D/        ( 4220): Cust_ConnectToPC   : IPT>true
,D/        ( 4220): Cust_ConnectToPC   : Singel_USB>false
I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
,I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b5e058
I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
,W/Settings( 4220): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMN     (  905): goingToSleep
,D/PMS     (  905): acquireWL(426bf9c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
E/SmartNS_Utility( 4220): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4220): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4220): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4220): onReceive:android.intent.action.USER_PRESENT
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19029 mDataStallAlarmIntent=PendingIntent{4267c1e8: PendingIntentRecord{4232f850 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:Off
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1160): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
I/SmartNS_PSService( 4220): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  905):    returned true
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/Settings( 4220): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4220):  defaultType:0
W/ContextImpl( 4220): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): acquireWL(42718938): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(426bf9c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/NetworkPolicy(  905): updateScreenOn: false
D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
D/ContactMessageStore( 1243): Background delete complete
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(42718938): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
D/SmartSyncUtils( 4363): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41bd63e0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  905): New client listening to asynchronous messages
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41bd63e0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41bd63e0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41bd63e0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@420a1438 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@420a1438 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1582): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(426d6e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1826): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1826): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1826): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1826): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1826): onScreenOff
D/PMS     (  905): releaseWL(426d6e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1401): service - mHandler: cancel location update
,D/AutoSetting( 1401): service -           changes count: 0
,D/PMS     (  905): acquireWL(42650230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42650230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4037
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4037:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4037
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3920
,I/ActivityManager(  905): Killing 3920:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3920
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4242f9f0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  905): acquireWL(42737780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42737780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(427007d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=136017, Int=0
,D/PMS     (  905): releaseWL(427007d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4271c950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{424ba2a0: PendingIntentRecord{424ee050 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140578, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{424e7028: PendingIntentRecord{424c6470 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140908, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
,D/PMS     (  905): acquireWL(427311f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  905): releaseWL(4271c950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9d2b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  905): acquireWL(426b4d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  905): releaseWL(426b4d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/AutoSetting( 1401): service - handleMessage() stop self
,D/AutoSetting( 1401): service - handleMessage() quit looper
,D/AutoSetting( 1401): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3585
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3585:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 9
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
,D/libc    (  905): [NET] getaddrinfo+,hn 12(0x35342e3139322e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,I/ActivityManager(  905): Recipient 3585
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(427311f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(426e2ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426e2ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4238b608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{425a58e8: PendingIntentRecord{42336308 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174178, Int=0
,D/PMS     (  905): releaseWL(4238b608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/PMS     (  905): acquireWL(426572e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426572e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42658360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=196017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42658360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4265a698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1582): [EventService] reorderNotification, total:0
D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  905): releaseWL(4265a698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1611): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HtcPowerSaver(  905): updateBatteryInfo
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4220): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4220): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4220): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4220): Cust_ConnectToPC   : spcsc>false
,D/        ( 4220): Cust_ConnectToPC   : IPT>true
D/        ( 4220): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4220): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,D/SmartNS_NSReceiver( 4220): Index of the first 1 = -1
W/ContextImpl( 4220): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4220): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4220): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4220): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4220): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 4220): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4260a7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4260a7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42732c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=256017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42732c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(427353a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/PMS     (  905): acquireWL(42735bf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,V/AlarmManager(  905): sending alarm PendingIntent{41d3be98: PendingIntentRecord{42478a88 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=280019, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4401 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{4262ee20: PendingIntentRecord{425d88f0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455035903368, Int=10800000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42706110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(427353a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10047}
,D/PMS     (  905): releaseWL(42735bf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(42706110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4401/10047)
,D/Process (  905): killProcessQuiet, pid=4087
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4087:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4087
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42699e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42699e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4269af08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=316017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4269af08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(4269d630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{426ed030: PendingIntentRecord{4256ef00 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1455036040500, Int=0
,D/PMS     (  905): releaseWL(4269d630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 2229): No account for auth token provided
,D/libc    ( 2229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2229): [NET] getaddrinfo-,err=8
D/libc    ( 2229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2229): [NET] getaddrinfo-, 1
,D/libc    ( 2229): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e6b4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 218
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2229): [NET] getaddrinfo_proxy-, success
I/global  ( 2229): call createSocket() return a new socket.
D/libc    ( 2229): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2229): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2229): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1582): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1582): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/PlayEventLogger( 4160): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4160): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4160): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4160): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4160): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4160): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4160): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4160): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e95e48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 18 6 12
,D/libc    ( 4160): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4160): [NET] getaddrinfo-,err=8
D/libc    ( 4160): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4160): [NET] getaddrinfo-, 1
,D/libc    ( 4160): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f34a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4160): [NET] getaddrinfo_proxy-, success
I/global  ( 4160): call createSocket() return a new socket.
D/libc    ( 4160): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4160): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4160): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4160): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(427bab40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427bab40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(427bbbb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=376017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427bbbb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(427bdeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427bdeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427bef28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=436017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427bef28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(427c1308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427c1308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(427c2380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=496017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427c2380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(427c4678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427c4678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427c56f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=556017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427c56f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427c7fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427c7fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(427c9048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=616017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427c9048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  905): acquireWL(427cb340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/BatteryService(  905): n_update end
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(427cb340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1582): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1582): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/Process (  905): killProcessQuiet, pid=3987
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3987:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3987
,D/PMS     (  905): acquireWL(427d5450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427d5450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427d64c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=676017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427d64c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427d87e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427d87e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427d9858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=736017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427d9858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427dc160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427dc160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427dd1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=796017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427dd1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427dfab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427dfab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427e0c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=856017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427e0c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427e2e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427e2e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427e3ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=916017, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427e3ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427e61b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427e61b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427e7230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=976017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427e7230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427ea470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41d8cbd8: PendingIntentRecord{42417300 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784197, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{42593cf8: PendingIntentRecord{424c7aa0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=927235, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{424e6260: PendingIntentRecord{424c4da8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455036623655, Int=900000
,V/AlarmManager(  905): sending alarm PendingIntent{42316450: PendingIntentRecord{4265e198 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455036694836, Int=0
,D/PMS     (  905): acquireWL(427f7e40): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): releaseWL(427f7e40): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  905): acquireWL(427fd000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(427fd000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4363): call getInstance()
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4363): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4363): [updateNmRange] bManual = false
D/PMS     (  905): acquireWL(427fea00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4363 1000 null
,D/PMS     (  905): releaseWL(427ea470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4363): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4363): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4363): SettingOnTime = 1455084000000, randomSettingOnTime = 1455083802000
D/SmartSyncScreenOnOffTimeReceiver( 4363): SettingOffTime = 1455062400000, randomSettingOffTime = 1455064939000
D/SmartSyncScreenOnOffTimeReceiver( 4363): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4363): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4363): bNightModeTurnOffOnce = false
D/PMS     (  905): acquireWL(428002c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/PMS     (  905): releaseWL(427fea00): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  905): releaseWL(428002c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(42832370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  905): releaseWL(42832370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  905): acquireWL(427c3ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427c3ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427c4e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1036017, Int=0
,D/PMS     (  905): releaseWL(427c4e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427d8740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427d8740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427dbcc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1096017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  905): releaseWL(427dbcc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427e06c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427e06c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427e3630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1156017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427e3630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4282f6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4282f6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(42636be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1216017, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42636be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426f0258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426f0258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(426ba1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{422e8430: PendingIntentRecord{41e67040 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1276017, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426ba1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4430): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4430): ====startRecUseTime====
D/htc.customization.log.level( 4430):  is 
W/CustomizationLogLevel( 4430): Level value is invalid, use default level 2
D/CustomizationManager( 4430):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4430): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4430): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4430): Parsing tag category name = system
I/CustomizationCIDLoader( 4430): Parsing tag category name = application
I/CustomizationCIDLoader( 4430): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4430): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4430): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4430): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4430): Parsing tag category name = Settings
D/CustomizationManager( 4430):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4430):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 4430): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4430): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4430): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4430): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4430, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  905): Skipping PackageSetting{421f83c8 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
W/PackageManager(  905): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  905): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1582): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1582): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1582): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
I/acms    ( 1901): Unregistering com.test.thalitest
E/acms    ( 1901): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1429): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(42835e38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
D/PMS     (  905): releaseWL(42835e38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  905):   Scheme: "sms"
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
D/PackageBroadcastService( 2229): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4443 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/MultiDex( 4443): install
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4443): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/ActivityManager(  905): Delaying start of: ServiceRecord{426b16c0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4443): loading existing secondary dex files
I/MultiDex( 4443): load found 1 secondary dex files
I/MultiDex( 4443): install done
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2229): CP2 sync disabled
I/Icing   ( 2229): doRemovePackageData com.test.thalitest
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2229, uid=10028, userID:0
D/PMS     (  905): acquireWL(424dde70): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
D/PMS     (  905): releaseWL(424dde70): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4443): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4463 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4463): install
I/MultiDex( 4463): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4463): loading existing secondary dex files
I/MultiDex( 4463): load found 1 secondary dex files
I/MultiDex( 4463): install done
I/ProviderInstaller( 4463): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Resuming delayed broadcast
E/SQLiteDatabase( 4443): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4443): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4443): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4443): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4443): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4443): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4443): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4443): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4443): threadid=12: thread exiting with uncaught exception (group=0x416abe30)
E/SharedPreferencesImpl( 1206): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/AndroidRuntime( 4443): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4443): Process: com.google.android.gms.drive, PID: 4443
E/AndroidRuntime( 4443): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4443): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4443): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4443): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4443): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4443): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4443): 	at ctn.run(SourceFile:985)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
I/[PluginManager]RegisterService( 1401): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1401): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1401): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9a2838
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
W/[PluginManager]RegisterService( 1401): provider may killed!
W/[PluginManager]RegisterService( 1401): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1401): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1401): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1401): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1401): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1401): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1401): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1401): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1401): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1401): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1401): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1401): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1401): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 4443): killProcess, pid=4443
D/Process ( 4443): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/[PluginManager]RegisterService( 1401): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Resuming delayed broadcast
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2901): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/SQLiteLog( 2901): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2901): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca231f0
W/dalvikvm( 2901): threadid=14: thread exiting with uncaught exception (group=0x416abe30)
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
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  905): Recipient 4443
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4443) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4485 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/Process ( 2901): killProcess, pid=2901
D/Process ( 2901): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
W/PackageManager(  905): Unable to load service info ResolveInfo{425cbae0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  905): Recipient 2901
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2901): Died!
D/WifiService(  905): Client connection lost with reason: 4
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2901) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
E/SQLiteDatabase( 2229): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2229): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2229): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2229): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2229): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2229): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2229): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2229): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2229): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2229): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2229): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2229): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2229): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2229): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2229): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2229): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2229): 	at java.lang.Thread.run(Thread.java:864)
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
E/SQLiteOpenHelper( 2229): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2229): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2229): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2229): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2229): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2229): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2229): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2229): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2229): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2229): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2229): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2229): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2229): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2229): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2229): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2229): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2229): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 2229): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 2229): threadid=10: thread exiting with uncaught exception (group=0x416abe30)
E/AndroidRuntime( 2229): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2229): Process: com.google.android.gms, PID: 2229
E/AndroidRuntime( 2229): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2229): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2229): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2229): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2229): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2229): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2229): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2229): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2229): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2229): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2229): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2229): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2229): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2229): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2229): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2229): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2229): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2229): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
D/Process (  905): killProcessQuiet, pid=2229
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
W/ActivityManager(  905): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  905): Killing 2229:com.google.android.gms/u0a28 (adj 6): crash
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
E/SQLiteDatabase( 4485): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4485): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4485): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4485): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4485): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4485): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4485): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4485): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4485): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4485): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4485): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4485): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4485): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4485): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4485): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4485): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4485): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4485): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4485): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4485): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4485): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4485): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4485): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4485): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4485): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4485): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4485): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4485): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4485): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4485): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4485): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4485): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4485): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4485): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4485): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4485): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4485): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4485): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4485): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4485): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4485): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4485): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4485): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4485): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4485): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4485): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4485): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4485): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4485): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4485): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4485): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4485): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4485): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4485): threadid=11: thread exiting with uncaught exception (group=0x416abe30)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4485): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4485): Process: com.google.android.apps.docs, PID: 4485
E/AndroidRuntime( 4485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4485): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4485): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4485): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4485): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4485): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
E/SQLiteDatabase( 4485): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4485): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4485): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4485): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4485): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4485): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4485): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4485): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4485): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4485): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4485): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4485): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4485): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4485): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4485): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4485): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4485): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4485): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4485): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4485): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4485): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4485): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4485): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4485): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4485): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4485): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4485): killProcess, pid=4485
D/Process ( 4485): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4504 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Recipient 4485
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  905): killProcessQuiet, pid=4198
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4198:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4485) has died.
W/ContextImpl( 4504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4504): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4504): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4504): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4504): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4504): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4504): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4504): threadid=10: thread exiting with uncaught exception (group=0x416abe30)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4517 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4504): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4504): Process: com.android.keychain, PID: 4504
E/AndroidRuntime( 4504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4504): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4504): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4504): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4504): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4504): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455036965672.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Recipient 4198
D/Process ( 4504): killProcess, pid=4504
D/Process ( 4504): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4504
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4504) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10363ms
D/AppTag  ( 4517): getInstance(Context context)
D/AppTag  ( 4517): getInstance(Context context)
D/AppTag  ( 4517): onCreate()
I/ActivityManager(  905): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4532 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}

```
